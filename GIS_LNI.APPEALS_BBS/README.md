# LNI_Appeals_BBS

### Summary  

The Board of Building Standards (BBS) is an advisory board that reviews  
appeals related to building safety and the application of Philadelphias Building Code.  
  
Data Development: Data Development: BBS data is entered into LNIs Hansen application and stored in its backend Oracle databases. Each night at 3am data from relevant LNI Oracle tables are generated into GIS layers on Geodb2 which was created via Phila.gov 2.0 initiative.  
Each Appeal has a unique Appeal Key that can be used to get further information about that appeal. Such information about each appeal includes an appeal number, application type, grounds (reason) for the appeal, the primary applicant applying for the appeal, and the associated Case or Permit. Further information includes  
the date of a previous or upcoming hearing and the decisions made at previous hearings. If an Appeal is denied, an applicant may progress the Appeal to Court. If the Appeal progresses to Court, information is available for the resulting Court Case once a decision has been reached, including the action date, case number, court action, court result, and any provisos.  


### Description  

Fields of Interest:APPEAL_NUM: Appeal numberAPPEAL_KEY: Appeal KeyADDDTTM: Date Appeal addedADDRKEY: Hansen Address KeyTYPE: Application typeCAPACITY:GROUNDS: Description of appealPRIMARY_APPLICANT:PERMIT_NO:  PERMIT_TYPE: Type of permit originally applied forPERMIT_WORK_TYPE: Unit of Licenses and InspectionsVIOLATION_ADDRESS:  

### Data Dictionary

| Field | Description  
| ----- | :----------:  
| APPEAL_NUM |  
| APPEAL_KEY |  
| ADDDTTM |  
| ADDRKEY |  
| TYPE |  
| CAPACITY |  
| GROUNDS |  
| PRIMARY_AP |  
| PERMIT_NO |  
| PERMIT_TYP |  
| PERMIT_WOR |  
| VIOLATION_ |  
| X |  
| Y |  
| ORIG_FID |  


### Use Limitations  

None