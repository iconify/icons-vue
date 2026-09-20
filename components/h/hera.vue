<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGbFfWmd9v)" class="j59akeyve"/><path fill="url(#SVGjJ8MvbFW)" class="wb2umqb3j"/><path fill="url(#SVGGADbPd4T)" class="ry9t8br7b"/><path fill="url(#SVGxVhWcdvs)" class="uiqcvnb0o"/><path fill="url(#SVGgJrnKevy)" class="nv-pjubwm"/><path fill="url(#SVGvCC7uduK)" class="vrniw_foq"/><path fill="url(#SVGdmjM9bWW)" class="zel3fs9co"/><path class="o132jbbtw"/><path fill="url(#SVGusqaJceF)" class="u7jua95qs"/><path fill="url(#SVGjwoCnWLI)" class="nkj9upvut"/><path class="wkstusxng"/><path fill="url(#SVGfHCmekSK)" class="swa2ezbnk"/><path fill="url(#SVGo0Xp1bqo)" class="gof16_bac"/><path fill="url(#SVGwp6cWbDw)" class="dzr-09zzc"/><path fill="url(#SVGSfaCvdzt)" class="qf-cthb-b"/><path fill="url(#SVGbp5d3ctB)" class="yb5--h0ey"/><path fill="url(#SVGNZ1pcdva)" class="vulazduac"/><path fill="url(#SVGKZ18So3y)" class="rc2htabgw"/><path fill="url(#SVG55JTeOGO)" class="eyyojacfc"/><path fill="url(#SVGdJIRSxvc)" class="d29-d_6km"/><path fill="url(#SVGhlw5wbSr)" class="ewe5h7-sk"/><path fill="url(#SVGewAExcah)" class="dvprv4bhi"/><path fill="url(#SVGs61pSbVu)" class="p6hr9gbel"/><path fill="url(#SVG6oMM0dJV)" class="zy-dyjbcp"/><path class="eud0rzbfp"/><path fill="url(#SVGWNqFjeTp)" class="t8sp6obnr"/><path fill="url(#SVGb406seJW)" class="ihpq21b2z"/><path class="u6h9a_bzi"/><path fill="url(#SVGzHPAMbwM)" class="pptckv-ei"/><path fill="url(#SVGo3kSMbCJ)" class="qn9e8c5vo"/><path fill="url(#SVGJIud1cOP)" class="z6co51swv"/><path fill="url(#SVGyC89Kcax)" class="j0juq2gia"/><path fill="url(#SVGRc8A6cZG)" class="g0ozc7bew"/><path fill="url(#SVG0P7NCdAw)" class="quc-ljcdf"/><path fill="url(#SVG9LJmrdqR)" class="wsx1dhb8l"/><path class="t3qm8-2cl"/><path class="qvtwi5bex"/><path class="umptxtbeu"/><path class="d_63cgbge"/><path class="il48cf_oz"/><path fill="url(#SVG8i3eKd8e)" class="tuefaccdr"/><path class="p_o_qjbrq"/><path class="l2c5tlb6f"/><path fill="url(#SVGQ38dHcEm)" class="dvoh12s_a"/><path class="ak88fzyrm"/><path class="v2yz1vp5a"/><path class="in0zwlbzq"/><path class="e_9xpsb9y"/><path class="eqf4b120q"/><path fill="url(#SVGwhZh3dxd)" class="v_blhkbvf"/><path class="d0r4-xbea"/><path class="vslz9qnoy"/><path fill="url(#SVGI3eufczU)" class="ftj1lgdtb"/><path fill="url(#SVGyJBRUdaC)" class="p4-21_b4d"/><path fill="url(#SVGB7dUze5B)" class="iy56gtb6s"/><path fill="url(#SVGaAQOvdfs)" class="a-n8-vb8h"/><path class="x2jfu5g_c"/><path fill="url(#SVGKZxvmorg)" class="w2aj1ybzn"/><path class="i88op_o_q"/><path class="rfle-yo8y"/><path fill="url(#SVGROLASbfC)" class="bv6wzdybb"/><path class="j6dr3obiu"/><path class="i48k5ybre"/><path class="otfhg2bbs"/><path fill="url(#SVGIQfJLb6z)" class="unj05t3_y"/><path fill="url(#SVGNduNYbtY)" class="n49g6-bec"/><path fill="url(#SVGwJT3teox)" class="b1car5iwt"/><path class="cypm5dsqu"/><path class="w1jqanb5f"/><path fill="url(#SVGcvZmqcfv)" class="d1faa7b8e"/><path class="c7hfr4zox"/><path fill="url(#SVGqDL0kVdt)" class="pgmdnyb7w"/><path fill="url(#SVGSUqvcdYN)" class="jkccme6dp"/><path fill="url(#SVGBM90Id0u)" class="vu_3racob"/><path class="fqzuz729e"/><path fill="url(#SVG69PUxbOP)" class="m6vyslf_u"/><path fill="url(#SVGZ6Yqjd7H)" class="pb6dk7kbl"/><path class="oaxs92kcp"/><path class="n74bractx"/><path class="embie2h9a"/><path fill="url(#SVG28hz5h0c)" class="ffw02ccht"/><path fill="url(#SVGchf6heTr)" class="brsz91ckf"/><path fill="url(#SVGSuftziEY)" class="mb8s8wqez"/><path fill="url(#SVGoZtOzdqT)" class="b5ao_0bws"/><path fill="url(#SVG2WPhLded)" class="n_ypj9blg"/><path fill="url(#SVGQvOuQcun)" class="e9j8ykbdw"/><path fill="url(#SVG3sdfbdxN)" class="zollgim6s"/><path class="j4ixjpcns"/><path fill="url(#SVG9x22McMw)" class="uu_y1dr7v"/><path fill="url(#SVGzqTbGbsi)" class="n7q-3fuez"/><path fill="url(#SVGDr7eQeDt)" class="dhrrfgbyd"/><path fill="url(#SVG302ByqmJ)" class="ziq5t8bhu"/><path fill="url(#SVGXLtwqeVl)" class="uyukznbpa"/><path class="foljifbsa"/><path fill="url(#SVGSih6QH5U)" class="agnp0520m"/><path fill="url(#SVGTupsFdpH)" clip-rule="evenodd" class="fdze37bug"/><path fill="url(#SVGQdyDQbZd)" class="yw_u-7bgn"/><path fill="url(#SVGu2HWqcMg)" clip-rule="evenodd" class="wgzybhqow"/><path fill="url(#SVG0xI9ZV2d)" class="lpl7u72hp"/><path fill="url(#SVG6DdzpdUc)" clip-rule="evenodd" class="e99h75r2p"/><path class="j362dmjub"/><path fill="url(#SVGvkcNqeKr)" class="mn4dmmb2r"/><path class="t6vlumblz"/><path fill="url(#SVGenKuNcOb)" class="wbosulbty"/><path fill="url(#SVG2Sx02ZRO)" class="hskijgbgd"/><path fill="url(#SVGvZ5SPdLr)" clip-rule="evenodd" class="bvnscwxxg"/><path class="bpxt6hvdg"/><path fill="url(#SVGr8nwtbZR)" class="x7emutbbv"/><path class="lis6wus0f"/><path fill="url(#SVGxQSUnecE)" class="obq4j4bjn"/><path fill="url(#SVGDJjIkwJO)" class="p72-rqjig"/><path fill="url(#SVGIW2DnBLU)" class="csd6hgbgr"/><path fill="url(#SVGT7EDxT7O)" class="a5sq2_phf"/><path fill="url(#SVGuQ6KJYVR)" class="twrdk2boi"/><path class="mtdxtzbyk"/><path class="jsaugeb4g"/><defs><linearGradient id="SVGbFfWmd9v" x1="13.738" x2="13.667" y1="8.13" y2="17.896" gradientUnits="userSpaceOnUse"><stop offset=".11" class="qey2f0bsa"/><stop offset=".23" class="kz2p3vbtw"/><stop offset=".28" class="mxtp-2bbn"/><stop offset=".43" class="sxiw3wbga"/><stop offset=".56" class="hpkmyhb7q"/><stop offset="1" class="xr1bi6b-r"/></linearGradient><linearGradient id="SVGjJ8MvbFW" x1="6.947" x2="10.845" y1="16.669" y2="18.289" gradientUnits="userSpaceOnUse"><stop class="p5fwkxbof"/><stop offset=".24" class="swssssb7k"/><stop offset=".41" class="zcbo6vbdf"/><stop offset=".69" class="sq4y3_bfs"/><stop offset="1" class="f80ymbcrs"/></linearGradient><linearGradient id="SVGGADbPd4T" x1="3.768" x2="6.33" y1="5.62" y2="18.375" gradientUnits="userSpaceOnUse"><stop class="wzi8kgbcv"/><stop offset=".13" class="y2asf4dnb"/><stop offset=".21" class="iqst3-b8h"/><stop offset=".27" class="mw4l2vgpv"/><stop offset=".39" class="gcglvdbwe"/><stop offset=".51" class="mlmu-3b1h"/><stop offset=".88" class="i981ddbei"/><stop offset="1" class="mgagogbwn"/></linearGradient><linearGradient id="SVGxVhWcdvs" x1="3.621" x2="6.089" y1="6.089" y2="18.071" gradientUnits="userSpaceOnUse"><stop class="za1aw8bfm"/><stop offset=".23" class="doo4m3b4n"/><stop offset=".42" class="vo0bpof5f"/><stop offset=".47" class="j01i7kt2d"/><stop offset=".56" class="osa178cpr"/><stop offset=".89" class="o9bacs-rg"/><stop offset="1" class="p6yqf0zgy"/></linearGradient><linearGradient id="SVGgJrnKevy" x1="6.317" x2="6.497" y1="7.244" y2="8.603" gradientUnits="userSpaceOnUse"><stop class="g5w7ob2ex"/><stop offset=".09" class="g5s298-ox"/><stop offset=".75" class="cw5nb2imu"/><stop offset="1" class="dhbelce6q"/></linearGradient><linearGradient id="SVGvCC7uduK" x1="6.435" x2="6.511" y1="7.472" y2="8.093" gradientUnits="userSpaceOnUse"><stop class="wilor5buq"/><stop offset="1" class="nh45bwbrt"/></linearGradient><linearGradient id="SVGdmjM9bWW" x1="5.979" x2="7.145" y1="8.324" y2="8.286" gradientUnits="userSpaceOnUse"><stop class="jbqp28r_r"/><stop offset="1" class="n71f3kros"/></linearGradient><linearGradient id="SVGusqaJceF" x1="11.835" x2="7.383" y1="7.292" y2="7.87" gradientUnits="userSpaceOnUse"><stop class="gzjhf9byz"/><stop offset=".33" class="q2e2p0mtm"/><stop offset=".54" class="mx4euackb"/><stop offset="1" class="s6dnkoxpr"/></linearGradient><linearGradient id="SVGjwoCnWLI" x1="11.834" x2="7.348" y1="7.221" y2="7.974" gradientUnits="userSpaceOnUse"><stop class="bp7n1ix3g"/><stop offset=".19" class="dwuqjgb9m"/><stop offset=".26" class="llfn4bbcd"/><stop offset=".56" class="giv4mpb3a"/><stop offset="1" class="y7h6b0w5l"/></linearGradient><linearGradient id="SVGfHCmekSK" x1="7.292" x2="11.967" y1="7.803" y2="7.865" gradientUnits="userSpaceOnUse"><stop class="hvj2ivbni"/><stop offset=".32" class="nklpq44kw"/><stop offset=".89" class="uoi61c4tl"/><stop offset="1" class="auvjyvbul"/></linearGradient><linearGradient id="SVGo0Xp1bqo" x1="7.677" x2="9.784" y1="16.134" y2="16.963" gradientUnits="userSpaceOnUse"><stop class="fmf86dblp"/><stop offset=".61" class="bj_yye5uy"/><stop offset="1" class="dxr67cb9t"/></linearGradient><linearGradient id="SVGwp6cWbDw" x1="7.676" x2="9.784" y1="16.135" y2="16.964" gradientUnits="userSpaceOnUse"><stop class="i2d_x08nq"/><stop offset=".61" class="qkve6ibea"/><stop offset="1" class="x9-wmpnpy"/></linearGradient><linearGradient id="SVGSfaCvdzt" x1="11.413" x2="11.436" y1="16.358" y2="18.409" gradientUnits="userSpaceOnUse"><stop class="cg8076kjv"/><stop offset=".27" class="apfd18jyt"/><stop offset=".58" class="n87nh4jgb"/><stop offset=".83" class="omcvfq02s"/><stop offset="1" class="k_etvt9tm"/></linearGradient><linearGradient id="SVGbp5d3ctB" x1="9.372" x2="11.944" y1="15.955" y2="16.334" gradientUnits="userSpaceOnUse"><stop class="fz3ccrkda"/><stop offset=".34" class="sb02tqh1r"/><stop offset=".5" class="upa54prsj"/><stop offset=".68" class="vw08jibsn"/><stop offset=".81" class="csja5bctb"/><stop offset="1" class="c9as41byb"/></linearGradient><linearGradient id="SVGNZ1pcdva" x1="10.485" x2="11.858" y1="17.049" y2="17.783" gradientUnits="userSpaceOnUse"><stop class="txkv6dzmq"/><stop offset=".42" class="k8tldig_q"/><stop offset="1" class="ygja7ia_w"/></linearGradient><linearGradient id="SVGKZ18So3y" x1="10.313" x2="11.824" y1="16.911" y2="17.981" gradientUnits="userSpaceOnUse"><stop class="giquhabiu"/><stop offset=".36" class="bvj3x_vxm"/><stop offset=".63" class="qsfehi76q"/><stop offset="1" class="ix59hspuj"/></linearGradient><linearGradient id="SVG55JTeOGO" x1="16.969" x2="13.066" y1="16.669" y2="18.289" gradientUnits="userSpaceOnUse"><stop class="p5fwkxbof"/><stop offset=".24" class="swssssb7k"/><stop offset=".41" class="zcbo6vbdf"/><stop offset=".69" class="sq4y3_bfs"/><stop offset="1" class="f80ymbcrs"/></linearGradient><linearGradient id="SVGdJIRSxvc" x1="20.147" x2="17.585" y1="5.62" y2="18.375" gradientUnits="userSpaceOnUse"><stop class="wzi8kgbcv"/><stop offset=".13" class="y2asf4dnb"/><stop offset=".21" class="iqst3-b8h"/><stop offset=".27" class="mw4l2vgpv"/><stop offset=".39" class="gcglvdbwe"/><stop offset=".51" class="mlmu-3b1h"/><stop offset=".88" class="i981ddbei"/><stop offset="1" class="mgagogbwn"/></linearGradient><linearGradient id="SVGhlw5wbSr" x1="20.293" x2="17.825" y1="6.089" y2="18.071" gradientUnits="userSpaceOnUse"><stop class="za1aw8bfm"/><stop offset=".23" class="doo4m3b4n"/><stop offset=".42" class="vo0bpof5f"/><stop offset=".47" class="j01i7kt2d"/><stop offset=".56" class="osa178cpr"/><stop offset=".89" class="o9bacs-rg"/><stop offset="1" class="p6yqf0zgy"/></linearGradient><linearGradient id="SVGewAExcah" x1="17.598" x2="17.418" y1="7.245" y2="8.604" gradientUnits="userSpaceOnUse"><stop class="g5w7ob2ex"/><stop offset=".09" class="g5s298-ox"/><stop offset=".75" class="cw5nb2imu"/><stop offset="1" class="dhbelce6q"/></linearGradient><linearGradient id="SVGs61pSbVu" x1="17.48" x2="17.404" y1="7.472" y2="8.093" gradientUnits="userSpaceOnUse"><stop class="wilor5buq"/><stop offset="1" class="nh45bwbrt"/></linearGradient><linearGradient id="SVG6oMM0dJV" x1="17.93" x2="16.769" y1="8.324" y2="8.286" gradientUnits="userSpaceOnUse"><stop class="jbqp28r_r"/><stop offset="1" class="n71f3kros"/></linearGradient><linearGradient id="SVGWNqFjeTp" x1="12.081" x2="16.533" y1="7.292" y2="7.87" gradientUnits="userSpaceOnUse"><stop class="gzjhf9byz"/><stop offset=".33" class="q2e2p0mtm"/><stop offset=".54" class="mx4euackb"/><stop offset="1" class="s6dnkoxpr"/></linearGradient><linearGradient id="SVGb406seJW" x1="12.08" x2="16.566" y1="7.221" y2="7.974" gradientUnits="userSpaceOnUse"><stop class="bp7n1ix3g"/><stop offset=".19" class="dwuqjgb9m"/><stop offset=".26" class="llfn4bbcd"/><stop offset=".56" class="giv4mpb3a"/><stop offset="1" class="y7h6b0w5l"/></linearGradient><linearGradient id="SVGzHPAMbwM" x1="16.618" x2="11.943" y1="7.803" y2="7.865" gradientUnits="userSpaceOnUse"><stop class="hvj2ivbni"/><stop offset=".32" class="nklpq44kw"/><stop offset=".89" class="uoi61c4tl"/><stop offset="1" class="auvjyvbul"/></linearGradient><linearGradient id="SVGo3kSMbCJ" x1="16.235" x2="14.132" y1="16.134" y2="16.963" gradientUnits="userSpaceOnUse"><stop class="fmf86dblp"/><stop offset=".61" class="bj_yye5uy"/><stop offset="1" class="dxr67cb9t"/></linearGradient><linearGradient id="SVGJIud1cOP" x1="16.24" x2="14.132" y1="16.135" y2="16.964" gradientUnits="userSpaceOnUse"><stop class="i2d_x08nq"/><stop offset=".61" class="qkve6ibea"/><stop offset="1" class="x9-wmpnpy"/></linearGradient><linearGradient id="SVGyC89Kcax" x1="12.502" x2="12.478" y1="16.358" y2="18.409" gradientUnits="userSpaceOnUse"><stop class="cg8076kjv"/><stop offset=".27" class="apfd18jyt"/><stop offset=".58" class="n87nh4jgb"/><stop offset=".83" class="omcvfq02s"/><stop offset="1" class="k_etvt9tm"/></linearGradient><linearGradient id="SVGRc8A6cZG" x1="14.544" x2="11.972" y1="15.955" y2="16.334" gradientUnits="userSpaceOnUse"><stop class="fz3ccrkda"/><stop offset=".34" class="sb02tqh1r"/><stop offset=".5" class="upa54prsj"/><stop offset=".68" class="vw08jibsn"/><stop offset=".81" class="csja5bctb"/><stop offset="1" class="c9as41byb"/></linearGradient><linearGradient id="SVG0P7NCdAw" x1="13.43" x2="12.056" y1="17.049" y2="17.783" gradientUnits="userSpaceOnUse"><stop class="txkv6dzmq"/><stop offset=".42" class="k8tldig_q"/><stop offset="1" class="ygja7ia_w"/></linearGradient><linearGradient id="SVG9LJmrdqR" x1="13.601" x2="12.085" y1="16.911" y2="17.981" gradientUnits="userSpaceOnUse"><stop class="giquhabiu"/><stop offset=".36" class="bvj3x_vxm"/><stop offset=".63" class="qsfehi76q"/><stop offset="1" class="ix59hspuj"/></linearGradient><linearGradient id="SVG8i3eKd8e" x1="3.187" x2="3.973" y1="11.612" y2="12.597" gradientUnits="userSpaceOnUse"><stop class="oho10q29i"/><stop offset="1" class="ty9x7ebll"/></linearGradient><linearGradient id="SVGQ38dHcEm" x1="3.967" x2="4.853" y1="13.917" y2="14.107" gradientUnits="userSpaceOnUse"><stop class="s9zdhr5-n"/><stop offset=".51" class="h-pf9_bvl"/><stop offset="1" class="tntj13thg"/></linearGradient><linearGradient id="SVGwhZh3dxd" x1="20.814" x2="20.028" y1="11.612" y2="12.597" gradientUnits="userSpaceOnUse"><stop class="oho10q29i"/><stop offset="1" class="ty9x7ebll"/></linearGradient><linearGradient id="SVGI3eufczU" x1="20.032" x2="19.146" y1="13.917" y2="14.107" gradientUnits="userSpaceOnUse"><stop class="s9zdhr5-n"/><stop offset=".51" class="h-pf9_bvl"/><stop offset="1" class="tntj13thg"/></linearGradient><linearGradient id="SVGyJBRUdaC" x1="6.998" x2="6.998" y1="9.707" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGB7dUze5B" x1="7.345" x2="7.345" y1="9.792" y2="11.682" gradientUnits="userSpaceOnUse"><stop offset=".11" class="mcusuaboz"/><stop offset=".26" class="vfa93d36o"/><stop offset=".33" class="y1ioq5bib"/><stop offset=".59" class="nuc_lwbeu"/><stop offset=".67" class="c8mvb_bfp"/><stop offset=".83" class="cpcvynb6m"/><stop offset="1" class="wig9qtbgj"/></linearGradient><linearGradient id="SVGaAQOvdfs" x1="8.752" x2="8.752" y1="9.707" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGKZxvmorg" x1="7.875" x2="7.875" y1="9.086" y2="12.292" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGROLASbfC" x1="8.406" x2="8.406" y1="9.792" y2="11.682" gradientUnits="userSpaceOnUse"><stop offset=".11" class="mcusuaboz"/><stop offset=".26" class="vfa93d36o"/><stop offset=".33" class="y1ioq5bib"/><stop offset=".37" class="fkpatmanp"/><stop offset=".59" class="nuc_lwbeu"/><stop offset=".67" class="c8mvb_bfp"/><stop offset=".83" class="cpcvynb6m"/><stop offset="1" class="wig9qtbgj"/></linearGradient><linearGradient id="SVGIQfJLb6z" x1="10.001" x2="10.001" y1="9.707" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGNduNYbtY" x1="10.29" x2="10.29" y1="9.707" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".04" class="fcd8tuppp"/><stop offset=".08" class="t7ysynb7s"/><stop offset=".14" class="b9h46fxle"/><stop offset=".33" class="bpad70bew"/><stop offset=".39" class="v0hbuw06s"/><stop offset=".42" class="fkpatmanp"/><stop offset=".5" class="legevmbog"/><stop offset=".6" class="y_155ubza"/><stop offset=".67" class="v_ck__bhy"/><stop offset=".88" class="cm_9dvf6b"/><stop offset=".94" class="d0aer9ffr"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGwJT3teox" x1="9.717" x2="11.398" y1="11.782" y2="11.668" gradientUnits="userSpaceOnUse"><stop class="w2h3bbbfx"/><stop offset=".33" class="d_lcdobeq"/><stop offset=".55" class="dxo3ddczl"/><stop offset="1" class="qblcy-blj"/></linearGradient><linearGradient id="SVGcvZmqcfv" x1="10.551" x2="10.551" y1="9.086" y2="12.302" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGqDL0kVdt" x1="11.166" x2="10.129" y1="9.574" y2="9.825" gradientUnits="userSpaceOnUse"><stop class="dd24mgbeb"/><stop offset=".53" class="onhyjw0fx"/><stop offset="1" class="w6r_bnhhz"/></linearGradient><linearGradient id="SVGSUqvcdYN" x1="11.361" x2="11.361" y1="13.368" y2="15.348" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGBM90Id0u" x1="11.711" x2="11.711" y1="13.368" y2="15.348" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".06" class="fcd8tuppp"/><stop offset=".08" class="t7ysynb7s"/><stop offset=".14" class="b9h46fxle"/><stop offset=".33" class="bpad70bew"/><stop offset=".39" class="v0hbuw06s"/><stop offset=".42" class="fkpatmanp"/><stop offset=".5" class="legevmbog"/><stop offset=".6" class="y_155ubza"/><stop offset=".67" class="v_ck__bhy"/><stop offset=".88" class="cm_9dvf6b"/><stop offset=".94" class="d0aer9ffr"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVG69PUxbOP" x1="12.526" x2="11.489" y1="13.237" y2="13.488" gradientUnits="userSpaceOnUse"><stop class="dd24mgbeb"/><stop offset=".53" class="onhyjw0fx"/><stop offset="1" class="w6r_bnhhz"/></linearGradient><linearGradient id="SVGZ6Yqjd7H" x1="11.077" x2="12.763" y1="15.447" y2="15.333" gradientUnits="userSpaceOnUse"><stop class="w2h3bbbfx"/><stop offset=".33" class="d_lcdobeq"/><stop offset=".55" class="dxo3ddczl"/><stop offset="1" class="qblcy-blj"/></linearGradient><linearGradient id="SVG28hz5h0c" x1="11.915" x2="11.915" y1="12.753" y2="15.969" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGchf6heTr" x1="12.242" x2="12.242" y1="9.707" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGSuftziEY" x1="12.587" x2="12.587" y1="9.631" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".02" class="nsdyjmb4d"/><stop offset=".14" class="upcbqqbkl"/><stop offset=".44" class="legevmbog"/><stop offset=".52" class="pijof0a3a"/><stop offset=".61" class="v_d9vacte"/><stop offset=".68" class="kwn_yqgrs"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGoZtOzdqT" x1="12.81" x2="13.852" y1="9.575" y2="11.844" gradientUnits="userSpaceOnUse"><stop offset=".02" class="iskb2bugy"/><stop offset=".12" class="yf-3s96du"/><stop offset=".28" class="es0s27ble"/><stop offset=".42" class="djlxzublo"/><stop offset=".52" class="n1trtbwzy"/><stop offset=".57" class="qoujutbnr"/><stop offset="1" class="gdem4kb3r"/></linearGradient><linearGradient id="SVG2WPhLded" x1="12.502" x2="14.103" y1="10.905" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="bnt2kteaq"/><stop offset=".24" class="l1w6x0byw"/><stop offset="1" class="m-7ct7bhz"/></linearGradient><linearGradient id="SVGQvOuQcun" x1="13.108" x2="13.108" y1="9.086" y2="12.302" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVG3sdfbdxN" x1="12.81" x2="13.435" y1="9.327" y2="10.743" gradientUnits="userSpaceOnUse"><stop class="lvq05bb8c"/><stop offset=".42" class="u2tijnjuy"/><stop offset=".59" class="ugsx3wbjm"/><stop offset=".68" class="doiniybay"/><stop offset="1" class="me09h5d8w"/></linearGradient><linearGradient id="SVG9x22McMw" x1="8.505" x2="8.505" y1="13.368" y2="15.348" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGzqTbGbsi" x1="8.852" x2="8.852" y1="13.368" y2="15.348" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".02" class="nsdyjmb4d"/><stop offset=".14" class="upcbqqbkl"/><stop offset=".44" class="legevmbog"/><stop offset=".52" class="pijof0a3a"/><stop offset=".61" class="v_d9vacte"/><stop offset=".68" class="kwn_yqgrs"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGDr7eQeDt" x1="9.072" x2="10.114" y1="13.236" y2="15.51" gradientUnits="userSpaceOnUse"><stop offset=".02" class="iskb2bugy"/><stop offset=".12" class="yf-3s96du"/><stop offset=".28" class="es0s27ble"/><stop offset=".42" class="djlxzublo"/><stop offset=".52" class="n1trtbwzy"/><stop offset=".57" class="qoujutbnr"/><stop offset="1" class="gdem4kb3r"/></linearGradient><linearGradient id="SVG302ByqmJ" x1="8.764" x2="10.365" y1="14.572" y2="15.642" gradientUnits="userSpaceOnUse"><stop class="bnt2kteaq"/><stop offset=".24" class="l1w6x0byw"/><stop offset="1" class="m-7ct7bhz"/></linearGradient><linearGradient id="SVGXLtwqeVl" x1="9.073" x2="9.698" y1="12.995" y2="14.411" gradientUnits="userSpaceOnUse"><stop class="lvq05bb8c"/><stop offset=".42" class="u2tijnjuy"/><stop offset=".59" class="ugsx3wbjm"/><stop offset=".68" class="doiniybay"/><stop offset="1" class="me09h5d8w"/></linearGradient><linearGradient id="SVGSih6QH5U" x1="9.372" x2="9.372" y1="12.753" y2="15.969" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGTupsFdpH" x1="15.58" x2="16.442" y1="9.537" y2="11.882" gradientUnits="userSpaceOnUse"><stop class="p5m98dapk"/><stop offset=".23" class="jkuzdybta"/><stop offset=".42" class="f7_frubvi"/><stop offset=".51" class="ba079nbws"/><stop offset=".6" class="fg0b1x82v"/><stop offset="1" class="cfi1cgbzd"/></linearGradient><linearGradient id="SVGQdyDQbZd" x1="15.818" x2="16.353" y1="9.726" y2="11.739" gradientUnits="userSpaceOnUse"><stop class="s5r_dzt0x"/><stop offset=".36" class="v8zcg6b8e"/><stop offset=".69" class="vpnwt3bic"/><stop offset="1" class="uz9r4gbrw"/></linearGradient><linearGradient id="SVGu2HWqcMg" x1="15.258" x2="16.49" y1="9.276" y2="12.246" gradientUnits="userSpaceOnUse"><stop class="effhzw9kj"/><stop offset=".28" class="c_87yqnay"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVG0xI9ZV2d" x1="6.316" x2="6.316" y1="12.753" y2="16.504" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVG6DdzpdUc" x1="6.317" x2="6.327" y1="13.095" y2="15.861" gradientUnits="userSpaceOnUse"><stop class="x1vbayu6s"/><stop offset=".61" class="i2cxjvv_o"/><stop offset="1" class="id43-44sc"/></linearGradient><linearGradient id="SVGvkcNqeKr" x1="6.34" x2="6.316" y1="13.491" y2="14.912" gradientUnits="userSpaceOnUse"><stop class="l7saelavo"/><stop offset=".19" class="elng2sc5z"/><stop offset=".4" class="lyfjlhbqd"/><stop offset=".93" class="smaluok0v"/><stop offset="1" class="d9hp-_brl"/></linearGradient><linearGradient id="SVGenKuNcOb" x1="6.231" x2="6.24" y1="15.201" y2="16.148" gradientUnits="userSpaceOnUse"><stop class="m-lbz7q7r"/><stop offset=".43" class="j6nbot4je"/><stop offset="1" class="uuqza_bml"/></linearGradient><linearGradient id="SVG2Sx02ZRO" x1="17.76" x2="17.76" y1="12.582" y2="16.333" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGvZ5SPdLr" x1="17.76" x2="17.77" y1="12.923" y2="15.689" gradientUnits="userSpaceOnUse"><stop class="x1vbayu6s"/><stop offset=".61" class="i2cxjvv_o"/><stop offset="1" class="id43-44sc"/></linearGradient><linearGradient id="SVGr8nwtbZR" x1="17.783" x2="17.759" y1="13.321" y2="14.742" gradientUnits="userSpaceOnUse"><stop class="l7saelavo"/><stop offset=".19" class="elng2sc5z"/><stop offset=".4" class="lyfjlhbqd"/><stop offset=".93" class="smaluok0v"/><stop offset="1" class="d9hp-_brl"/></linearGradient><linearGradient id="SVGxQSUnecE" x1="17.67" x2="17.68" y1="15.031" y2="15.978" gradientUnits="userSpaceOnUse"><stop class="m-lbz7q7r"/><stop offset=".43" class="j6nbot4je"/><stop offset="1" class="uuqza_bml"/></linearGradient><linearGradient id="SVGDJjIkwJO" x1="14.515" x2="14.515" y1="12.753" y2="15.969" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGIW2DnBLU" x1="14.553" x2="14.553" y1="13.095" y2="15.605" gradientUnits="userSpaceOnUse"><stop class="b617qxbmc"/><stop offset=".43" class="e5s14nblj"/><stop offset=".5" class="f2a3hrbti"/><stop offset=".54" class="dh3gfdb2p"/><stop offset=".83" class="q95xftbio"/><stop offset="1" class="ig-b6tpfw"/></linearGradient><linearGradient id="SVGT7EDxT7O" x1="15.235" x2="15.235" y1="13.095" y2="15.34" gradientUnits="userSpaceOnUse"><stop class="n7r3bdbrm"/><stop offset=".4" class="a18pqob7l"/><stop offset=".62" class="sq9oklbmf"/><stop offset=".67" class="w_ns7fs-b"/><stop offset="1" class="xtpkynb9n"/></linearGradient><linearGradient id="SVGuQ6KJYVR" x1="13.563" x2="15.126" y1="13.151" y2="15.018" gradientUnits="userSpaceOnUse"><stop class="fnevu203c"/><stop offset=".12" class="anp4xbbxy"/><stop offset="1" class="nwiyiqbom"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hera" /></template>
<style>
.a-n8-vb8h {
  d: path("M8.558 9.428h.37v2.524h-.37z");
}

.a-y59khlr {
  stop-color: var(--svg-color--3f354e, #3f354e);
}

.a18pqob7l {
  stop-color: var(--svg-color--d17811, #d17811);
}

.a5sq2_phf {
  d: path("M15.06 13.09h.35v2.25h-.35z");
}

.agnp0520m {
  d: path("M7.909 12.933a.35.35 0 0 1 .327-.223h1.222a1.075 1.075 0 0 1 1.051 1.07c0 .285-.109.53-.294.716c.176.393.431.748.555.895l.004.004a.33.33 0 0 1 .048.36a.35.35 0 0 1-.313.2h-.63a.35.35 0 0 1-.19-.053a1.1 1.1 0 0 1-.227-.203a.346.346 0 0 1-.336.255h-.89a.35.35 0 0 1-.327-.222a.33.33 0 0 1 .08-.355V13.33a.41.41 0 0 1-.08-.398m.327.156l.094.085v2.359l-.094.08h.89l-.1-.08v-.962h.053l.056.015l.029.023l.047.085v.005l.161.284c.142.237.332.521.507.63h.63a3.9 3.9 0 0 1-.692-1.198l-.014-.024v-.004a.7.7 0 0 0 .251-.237a.65.65 0 0 0 .11-.37a.7.7 0 0 0-.706-.691zm.79.317v.971a.39.39 0 0 0 .346-.19a.62.62 0 0 0 0-.587a.38.38 0 0 0-.345-.189z");
}

.ak88fzyrm {
  fill: var(--svg-color--c4802f, #c4802f);
  d: path("M20.146 10.214c-.1-1.16.52-1.563.805-2.013c0 .445-.061.824-.09.962c-.066.25-.469.544-.715 1.051");
}

.anp4xbbxy {
  stop-color: var(--svg-color--f1d361, #f1d361);
}

.apfd18jyt {
  stop-color: var(--svg-color--624025, #624025);
}

.auvjyvbul {
  stop-color: var(--svg-color--c9a454, #c9a454);
}

.b1car5iwt {
  d: path("m10.162 11.573l-.445.38h1.459l.213-.38z");
}

.b5ao_0bws {
  d: path("m13.307 10.74l.237-.014c.16.444.396.857.696 1.222c-.19-.076-.44-.175-.516-.237c-.085-.076-.469-.767-.483-.791c-.01-.024-.17-.109-.407-.123a.9.9 0 0 0-.422.085v-.17h.35c.285 0 .417-.237.417-.484c0-.246-.132-.52-.416-.52c-.1 0-.275.042-.35.061c.132-.137.307-.237.496-.218c.313.029.56.27.592.545c.034.25-.118.535-.194.644");
}

.b617qxbmc {
  stop-color: var(--svg-color--cd7b0f, #cd7b0f);
}

.b9h46fxle {
  stop-color: var(--svg-color--d49522, #d49522);
}

.ba079nbws {
  stop-color: var(--svg-color--a85c20, #a85c20);
}

.bj_yye5uy {
  stop-color: var(--svg-color--3f3124, #3f3124);
}

.bnt2kteaq {
  stop-color: var(--svg-color--844210, #844210);
}

.bp7n1ix3g {
  stop-color: var(--svg-color--644624, #644624);
}

.bpad70bew {
  stop-color: var(--svg-color--cd8a2a, #cd8a2a);
}

.bpxt6hvdg {
  fill: var(--svg-color--faf3d9, #faf3d9);
  d: path("m17.424 12.923l.237.398h.322l.265-.398z");
}

.brsz91ckf {
  d: path("M12 9.428h.412v2.524H12z");
}

.bv6wzdybb {
  d: path("M8.212 9.428h.346v2.524h-.346z");
}

.bvj3x_vxm {
  stop-color: var(--svg-color--efb15f, #efb15f);
}

.bvnscwxxg {
  fill-rule: evenodd;
  d: path("M17.424 12.923h.829l.843 2.79l.17.312l-.677-.445l-.199-.644h-.246l-.038.037h-.691l-.038-.037h-.246l-.2.644l-.681.445l.175-.313l1-2.794zm.085 1.804l-.047-.07l.284-1.057h.1l.208 1.056l-.085.071z");
}

.c_87yqnay {
  stop-color: var(--svg-color--4f476f, #4f476f);
}

.c7hfr4zox {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m10.162 9.796l-.445-.402h1.468l-.27.25c-.336-.014-.336-.014-.753.152");
}

.c8mvb_bfp {
  stop-color: var(--svg-color--bd6f2f, #bd6f2f);
}

.c9as41byb {
  stop-color: var(--svg-color--885532, #885532);
}

.cfi1cgbzd {
  stop-color: var(--svg-color--5b190d, #5b190d);
}

.cg8076kjv {
  stop-color: var(--svg-color--764a2f, #764a2f);
}

.cm_9dvf6b {
  stop-color: var(--svg-color--c78a5f, #c78a5f);
}

.cpcvynb6m {
  stop-color: var(--svg-color--c7936e, #c7936e);
}

.csd6hgbgr {
  d: path("m14.951 14.7l-1.09-1.61h-.44v2.51h.602v-1.35l.966 1.364h.8v-2.52h-.729V14.7z");
}

.csja5bctb {
  stop-color: var(--svg-color--8c5d33, #8c5d33);
}

.cw5nb2imu {
  stop-color: var(--svg-color--69380f, #69380f);
}

.cypm5dsqu {
  fill: var(--svg-color--591910, #591910);
  d: path("M10.162 11.573c.076.08.251.232.36.232h.46c.094 0 .317-.165.397-.232h.01l-.213.38h-1.46z");
}

.d_63cgbge {
  fill: var(--svg-color--30120a, #30120a);
  d: path("M3.048 9.759c0 .227.085.696.412 1.013c.274.275.364.616.379.834a1.8 1.8 0 0 0-.54-.71c-.346-.27-.332-.882-.251-1.137");
}

.d_lcdobeq {
  stop-color: var(--svg-color--ffeccf, #ffeccf);
}

.d0aer9ffr {
  stop-color: var(--svg-color--ffedd4, #ffedd4);
}

.d0r4-xbea {
  fill: var(--svg-color--331200, #331200);
  d: path("M20.024 13.492c.246 0 .416-.356.468-.521c-.36.232-.568.118-.757.132c-.142.01-.299.28-.356.412c.393-.303.332-.023.644-.023");
}

.d1faa7b8e {
  d: path("M10.58 10.521v-.73c.032-.009.023 0 .066 0h.052a.5.5 0 0 1 .317.11l.18-.507H9.727l.118.104v2.35l-.123.103h1.459l.213-.379h-.815v-.691h.052q.09 0 .17.033l.081.029l.256-.427h-.559zm.478.71h.331a.35.35 0 0 1 .299.171a.33.33 0 0 1 0 .332l-.209.326a.35.35 0 0 1-.303.176H9.717a.35.35 0 0 1-.322-.223c-.052-.133-.014-.227.095-.322h.005V9.687a.33.33 0 0 1-.1-.378a.34.34 0 0 1 .322-.223h1.469a.35.35 0 0 1 .284.142a.34.34 0 0 1 .047.313l-.175.473a.34.34 0 0 1-.138.17a.35.35 0 0 1 .284.337c0 .06-.016.12-.047.17l-.265.427a.34.34 0 0 1-.118.118z");
}

.d29-d_6km {
  d: path("M16.756 16.783v-.014l1.051-3.898c.943-1.516.82-2.68.436-3.855a1.78 1.78 0 0 1 .27-1.73c.488-.141 1.255-.643 2.103-1.68A4.1 4.1 0 0 1 20 6.685a7 7 0 0 1-.426.487c-.388.426-.777.853-.824 1.355c-.033.346.028.705.095 1.099c.047.274.094.568.113.88c.062.882-.473 2.004-.757 2.45l-.711 1.515l-.355 3.898l-.38-1.592z");
}

.d9hp-_brl {
  stop-color: var(--svg-color--f5f2ed, #f5f2ed);
}

.dd24mgbeb {
  stop-color: var(--svg-color--6e421d, #6e421d);
}

.dh3gfdb2p {
  stop-color: var(--svg-color--bf6616, #bf6616);
}

.dhbelce6q {
  stop-color: var(--svg-color--663517, #663517);
}

.dhrrfgbyd {
  d: path("m9.57 14.401l.236-.01c.161.443.397.855.697 1.218c-.19-.071-.436-.17-.512-.237c-.09-.07-.474-.762-.483-.786c-.014-.024-.175-.109-.407-.123a.9.9 0 0 0-.427.085v-.17h.35c.285 0 .422-.237.422-.483c0-.251-.137-.488-.426-.488c-.095 0-.27.042-.34.061c.127-.137.302-.236.492-.218c.317.024.563.237.596.512c.029.25-.123.53-.199.64");
}

.djlxzublo {
  stop-color: var(--svg-color--fff8f6, #fff8f6);
}

.doiniybay {
  stop-color: var(--svg-color--612711, #612711);
}

.doo4m3b4n {
  stop-color: var(--svg-color--3b2a1a, #3b2a1a);
}

.dvoh12s_a {
  d: path("M3.93 13.87c.084.08.27.199.482.19c.161 0 .294.009.408.037h.014c-.133-.241-.28-.255-.336-.227c-.308.095-.507.038-.569 0");
}

.dvprv4bhi {
  d: path("M18.512 7.287c-.223.246-.474.782-.341 1.468c-.09-.203-.327-.435-.82-.331l-1.264.251c.227-.289.734-.947.995-1.355c.217-.061.71-.132 1.17.01a1 1 0 0 0 .26-.043");
}

.dwuqjgb9m {
  stop-color: var(--svg-color--c38a3e, #c38a3e);
}

.dxo3ddczl {
  stop-color: var(--svg-color--f7f2ee, #f7f2ee);
}

.dxr67cb9t {
  stop-color: var(--svg-color--1b170e, #1b170e);
}

.dzr-09zzc {
  d: path("M10.026 17.376c.033.128-.02-.095 0 0a2.76 2.76 0 0 0-2.98-.962v.014h.161c.825-.009 1.781-.014 2.856 1.104z");
}

.e_9xpsb9y {
  fill: var(--svg-color--30120a, #30120a);
  d: path("M20.953 9.759a1.52 1.52 0 0 1-.413 1.013c-.22.224-.355.52-.378.834c.066-.156.217-.455.54-.71c.345-.27.331-.882.25-1.137");
}

.e5s14nblj {
  stop-color: var(--svg-color--c1660f, #c1660f);
}

.e99h75r2p {
  fill-rule: evenodd;
  d: path("M5.986 13.09h.824l.843 2.794l.175.265l-.682-.397l-.199-.645h-.246l-.038.034H5.97l-.038-.034h-.246l-.199.645l-.682.397l.175-.265l1-2.794zm.085 1.81l-.048-.072l.285-1.056h.094l.213 1.056l-.09.071z");
}

.e9j8ykbdw {
  d: path("M11.645 9.309a.34.34 0 0 1 .322-.223h1.226a1.043 1.043 0 0 1 1.052 1.032a1 1 0 0 1-.294.71c.17.399.426.754.554.9c.095.105.11.19.052.309a.35.35 0 0 1-.312.199h-.63a.35.35 0 0 1-.19-.053c-.08-.051-.16-.07-.232-.146l-.01.033c-.047.133-.18.166-.321.166h-.896a.35.35 0 0 1-.321-.223c-.048-.123-.015-.208.075-.298V9.664a.33.33 0 0 1-.075-.355m.322.118l.033.024v2.472l-.034.028h.896l-.1-.085v-.957h.052c.02 0 .038.01.052.015l.029.023l.047.09h.005l.161.284c.142.237.331.521.507.635h.63v-.005c-.3-.354-.535-.76-.692-1.198c-.01-.005-.01-.014-.014-.024a.7.7 0 0 0 .36-.606a.7.7 0 0 0-.706-.691h-1.226zm.795.275v1.013a.4.4 0 0 0 .346-.194a.6.6 0 0 0 .071-.294a.8.8 0 0 0-.071-.331a.38.38 0 0 0-.346-.19z");
}

.effhzw9kj {
  stop-color: var(--svg-color--877fa4, #877fa4);
}

.elng2sc5z {
  stop-color: var(--svg-color--4b1b05, #4b1b05);
}

.embie2h9a {
  fill: var(--svg-color--501f0c, #501f0c);
  d: path("m12.237 14.604l.265-.421l-.322.17h-.658v.194h.473q.086 0 .166.029l.08.033z");
}

.eqf4b120q {
  fill: var(--svg-color--2d0700, #2d0700);
  d: path("M20.279 12.038c.18-.322.474-.474.597-.512c-.114.11-.062.341-.275.839c-.175.417-.568.312-.715.203c.057-.042.218-.213.393-.53");
}

.es0s27ble {
  stop-color: var(--svg-color--e3ab3e, #e3ab3e);
}

.eud0rzbfp {
  fill: var(--svg-color--bca98a, #bca98a);
  d: path("M17.523 7.69c.11.023.19.142.214.198c-.17-.175-.412-.094-.512-.038c.057-.061.19-.175.298-.156z");
}

.ewe5h7-sk {
  d: path("m17.134 18.37l.35-3.893l.72-1.516c.275-.45.815-1.572.758-2.453c-.024-.313-.076-.607-.118-.881a4.4 4.4 0 0 1-.095-1.1c.047-.506.436-.932.824-1.354c.147-.16.299-.322.426-.488c.237-.308.46-.663.616-1.08a4.8 4.8 0 0 1-.72 1.895l-.256.398c-.36.545-.421.64-.303 1.733c.266 1.573-.184 2.373-.976 3.77l-.085.152l.152 2.728c-.346.45-1.08 1.502-1.288 2.113z");
}

.eyyojacfc {
  d: path("M13.317 17.881c.157-.203.445-.739.569-1.44v-.004c0-.1 0-.313.559-.592l.421.123c-.237.113-.71.36-.744.445c-.028.09-.17.677-.236.962a2.76 2.76 0 0 1 2.983-.962l-.075.38l-.029.013l-.01-.028a3.5 3.5 0 0 0-1.25-.062c-.492.076-.871.45-1.255.83c-.393.383-.79.771-1.316.847c.085-.095.284-.332.383-.512");
}

.f2a3hrbti {
  stop-color: var(--svg-color--c06614, #c06614);
}

.f7_frubvi {
  stop-color: var(--svg-color--e4a353, #e4a353);
}

.f80ymbcrs {
  stop-color: var(--svg-color--853210, #853210);
}

.fcd8tuppp {
  stop-color: var(--svg-color--6e390c, #6e390c);
}

.fdze37bug {
  fill-rule: evenodd;
  d: path("M16.234 11.953a1.28 1.28 0 0 0 1.156-1.421a1.34 1.34 0 0 0-1.497-1.127a1.3 1.3 0 0 0-1.151 1.44a1.33 1.33 0 0 0 1.492 1.112zm.227-.299c.233-.075.341-.677.19-1.122c-.175-.493-.687-.862-.919-.791c-.317.095-.37.753-.232 1.146c.19.535.796.815.961.767");
}

.ffw02ccht {
  d: path("M11.896 14.183v-.71a1 1 0 0 1 .16-.02q.097.001.186.039a.7.7 0 0 1 .137.07l.17-.473h-1.468l.123.109v2.311l-.128.104h1.464l.208-.379h-.852v-.686h.095a.5.5 0 0 1 .17.028l.08.033l.261-.426zm.52.715h.332c.123 0 .237.066.299.166a.33.33 0 0 1 .004.336l-.208.38a.34.34 0 0 1-.303.174h-1.464a.346.346 0 0 1-.336-.427a.33.33 0 0 1 .109-.174h.005v-2.004a.4.4 0 0 1-.1-.416a.34.34 0 0 1 .322-.223h1.473a.35.35 0 0 1 .285.142c.066.095.08.251.042.355l-.175.474a.34.34 0 0 1-.137.17a.32.32 0 0 1 .236.166a.33.33 0 0 1 0 .341l-.26.426a.34.34 0 0 1-.118.114z");
}

.fg0b1x82v {
  stop-color: var(--svg-color--582510, #582510);
}

.fkpatmanp {
  stop-color: var(--svg-color--fff8f2, #fff8f2);
}

.fmf86dblp {
  stop-color: var(--svg-color--060002, #060002);
}

.fnevu203c {
  stop-color: var(--svg-color--f8eaab, #f8eaab);
}

.foljifbsa {
  fill: var(--svg-color--591812, #591812);
  d: path("m8.68 15.238l-.445.38h.89z");
}

.fqzuz729e {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m11.527 13.469l-.45-.38h1.473l-.27.223c-.322-.047-.511-.014-.758.157z");
}

.ft5dv1b6b {
  fill: none;
}

.ftj1lgdtb {
  d: path("M20.07 13.87a.7.7 0 0 1-.483.19a1.7 1.7 0 0 0-.408.037h-.014c.133-.241.28-.255.332-.227c.312.095.511.038.573 0");
}

.fz3ccrkda {
  stop-color: var(--svg-color--746b44, #746b44);
}

.g0ozc7bew {
  d: path("M13.895 16.367c-.274.18-.559.332-.748.389a.8.8 0 0 0-.535 0l-.654-.313v-.208l.616.388c.095-.071.331-.17.544-.024c.015.015.067.034.176-.038q.585-.367 1.174-.729l.08.095c-.141.1-.33.237-.54.37l-.108.07z");
}

.g5s298-ox {
  stop-color: var(--svg-color--52371a, #52371a);
}

.g5w7ob2ex {
  stop-color: var(--svg-color--8d6029, #8d6029);
}

.gcglvdbwe {
  stop-color: var(--svg-color--efcf72, #efcf72);
}

.gdem4kb3r {
  stop-color: var(--svg-color--f0ece9, #f0ece9);
}

.giquhabiu {
  stop-color: var(--svg-color--be8542, #be8542);
}

.giv4mpb3a {
  stop-color: var(--svg-color--d9913c, #d9913c);
}

.gof16_bac {
  d: path("M10.064 17.532c-1.156-1.204-2.179-1.104-3.041-1.104l1.345-.654l.767.18l.659.403c.047.028.075.166.085.218l.19.957z");
}

.gzjhf9byz {
  stop-color: var(--svg-color--3f3126, #3f3126);
}

.h-pf9_bvl {
  stop-color: var(--svg-color--53250d, #53250d);
}

.hpkmyhb7q {
  stop-color: var(--svg-color--14122a, #14122a);
}

.hskijgbgd {
  d: path("M18.253 12.582c.156 0 .289.095.331.242l.83 2.747l.146.227a.336.336 0 0 1-.118.475a.35.35 0 0 1-.175.046h-1.061a.35.35 0 0 1-.336-.244a.3.3 0 0 1-.01-.144a.74.74 0 0 0-.033-.38h-.17l-.015.086a2 2 0 0 0-.01.313a.33.33 0 0 1-.09.26a.35.35 0 0 1-.255.109H16.25a.345.345 0 0 1-.348-.35a.33.33 0 0 1 .054-.171l.151-.237l.995-2.752a.34.34 0 0 1 .322-.227zm-1.923 3.396l.095-.265l1-2.795h.828l.843 2.795l.17.312h-1.06a1.5 1.5 0 0 0 0-.388a.8.8 0 0 0-.19-.426h-.578c-.095.109-.137.293-.151.464c-.01.118-.033.232-.029.303zm1.137-1.326l.057.075h.445l.08-.094l-.203-1.033h-.095l-.284 1.047z");
}

.hvj2ivbni {
  stop-color: var(--svg-color--fff3a7, #fff3a7);
}

.i2cxjvv_o {
  stop-color: var(--svg-color--f6f5f1, #f6f5f1);
}

.i2d_x08nq {
  stop-color: var(--svg-color--b78643, #b78643);
}

.i48k5ybre {
  fill: var(--svg-color--591812, #591812);
  d: path("m8.58 11.573l-.445.38h.89z");
}

.i88op_o_q {
  fill: var(--svg-color--591812, #591812);
  d: path("m7.168 11.573l-.445.38h.89z");
}

.i981ddbei {
  stop-color: var(--svg-color--75512d, #75512d);
}

.id43-44sc {
  stop-color: var(--svg-color--e8dcce, #e8dcce);
}

.ig-b6tpfw {
  stop-color: var(--svg-color--e8ba96, #e8ba96);
}

.ihpq21b2z {
  d: path("m16.04 8.675l1.014-1.345c-.034-.033-.374-.095-1.469-.085c-1.103.01-1.752-.166-1.932-.256a18 18 0 0 1-1.397-.73c-.123-.094-.251-.378-.299-.506V8.06l.01.104c.014 0 .024.019.028.038c.01.023.02.047.048.047h3.107c.483 0 .795.284.89.426m.616-1.184l-.53.71a1.5 1.5 0 0 0-1.029-.411H12.19a.28.28 0 0 0-.236-.133V7.22l.412-.303c.047-.019.17-.028.298.057c0-.047.028-.142.147-.095l.118.057c.26.133.834.417 1.492.474c.332.033.673.019 1 .004c.464-.019.9-.033 1.236.071z");
}

.il48cf_oz {
  fill: var(--svg-color--2d0700, #2d0700);
  d: path("M3.722 12.038a1.13 1.13 0 0 0-.597-.512c.114.11.062.341.275.839c.175.417.568.312.715.203c-.057-.042-.218-.213-.393-.53");
}

.in0zwlbzq {
  fill: var(--svg-color--fbc56b, #fbc56b);
  d: path("M20.44 10.545a1.4 1.4 0 0 0 .511-.791c.08.256.095.871-.25 1.137a1.8 1.8 0 0 0-.555.743c0-.227-.07-.781.294-1.09");
}

.iqst3-b8h {
  stop-color: var(--svg-color--fdefd2, #fdefd2);
}

.iskb2bugy {
  stop-color: var(--svg-color--60340f, #60340f);
}

.ix59hspuj {
  stop-color: var(--svg-color--f8c166, #f8c166);
}

.iy56gtb6s {
  d: path("M7.17 9.428h.345v2.524H7.17z");
}

.j01i7kt2d {
  stop-color: var(--svg-color--54250b, #54250b);
}

.j0juq2gia {
  d: path("M11.953 16.235c.16.094.502.312.62.388c.095-.071.332-.17.545-.024c.014.015.066.034.175-.038q.585-.367 1.175-.729l.094.114l-.663.426c-.1.725-.52 1.54-.592 1.54c-.322.042-1.023.18-1.35.482v-2.16z");
}

.j362dmjub {
  fill: var(--svg-color--faf3d9, #faf3d9);
  d: path("m5.985 13.09l.232.402h.322l.27-.397H5.98z");
}

.j4ixjpcns {
  fill: var(--svg-color--591812, #591812);
  d: path("m12.411 11.573l-.492.38h.975z");
}

.j59akeyve {
  d: path("M11.658 6.26c.119-.096.247-.38.299-.508v12.642c-.332-.303-1.033-.441-1.35-.484c.1.17.284.389.374.483c-.53-.075-.923-.464-1.317-.852c-.378-.374-.762-.748-1.26-.824a3.5 3.5 0 0 0-1.245.061l-.384 1.616c-.208-.616-.947-1.663-1.288-2.113l.147-2.728l-.085-.152c-.787-1.397-1.241-2.197-.971-3.77c.118-1.089.052-1.184-.303-1.733L4.019 7.5a4.8 4.8 0 0 1-.72-1.895C4.317 6.846 5.217 7.33 5.662 7.33a2.3 2.3 0 0 1 1.199 0c.033-.033.374-.094 1.468-.085c1.103.01 1.747-.166 1.932-.256c.417-.203 1.279-.63 1.397-.729m.597 0c-.123-.096-.25-.38-.298-.508v12.642c.327-.303 1.032-.441 1.35-.484q-.165.259-.375.483c.526-.075.924-.464 1.317-.852c.38-.374.758-.748 1.255-.824a3.5 3.5 0 0 1 1.25.061l.384 1.616c.209-.616.948-1.663 1.288-2.113l-.15-2.728l.084-.152c.791-1.397 1.241-2.197.976-3.77c-.118-1.089-.057-1.184.303-1.733l.256-.398a4.8 4.8 0 0 0 .72-1.895C19.596 6.846 18.697 7.33 18.25 7.33a2.3 2.3 0 0 0-1.198 0c-.033-.033-.374-.094-1.468-.085c-1.104.01-1.753-.166-1.933-.256c-.416-.203-1.278-.63-1.397-.729");
}

.j6dr3obiu {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m8.58 9.772l-.445-.378h.89z");
}

.j6nbot4je {
  stop-color: var(--svg-color--591700, #591700);
}

.jbqp28r_r {
  stop-color: var(--svg-color--ebb53b, #ebb53b);
}

.jkccme6dp {
  d: path("M11.205 13.094h.322v2.524h-.322z");
}

.jkuzdybta {
  stop-color: var(--svg-color--f3d49b, #f3d49b);
}

.jsaugeb4g {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m15.42 13.469l-.506-.38h.952z");
}

.k_etvt9tm {
  stop-color: var(--svg-color--873915, #873915);
}

.k8tldig_q {
  stop-color: var(--svg-color--372f22, #372f22);
}

.kmmdfcbdu {
  stop-color: var(--svg-color--948dae, #948dae);
}

.kwn_yqgrs {
  stop-color: var(--svg-color--bb631e, #bb631e);
}

.kz2p3vbtw {
  stop-color: var(--svg-color--3e1e54, #3e1e54);
}

.l1w6x0byw {
  stop-color: var(--svg-color--501e13, #501e13);
}

.l2c5tlb6f {
  fill: var(--svg-color--391101, #391101);
  d: path("M4.498 13.87c-.308.095-.507.038-.569 0c.142.208.299.308.408.341c.094.033.16-.029.246-.066c.128-.048.203-.048.25-.048c-.132-.241-.279-.255-.335-.227");
}

.l7saelavo {
  stop-color: var(--svg-color--502302, #502302);
}

.l9h1mqb9i {
  stop-color: var(--svg-color--1d0f28, #1d0f28);
}

.legevmbog {
  stop-color: var(--svg-color--c88131, #c88131);
}

.lis6wus0f {
  fill: var(--svg-color--4d0206, #4d0206);
  d: path("M17.287 16.025H16.25l.682-.445zm.919 0l.378-.445l.683.445z");
}

.llfn4bbcd {
  stop-color: var(--svg-color--f6e497, #f6e497);
}

.lpl7u72hp {
  d: path("M6.808 12.71c.157 0 .29.095.332.241l.829 2.79l.147.228a.33.33 0 0 1 .014.345a.34.34 0 0 1-.303.176H6.76a.35.35 0 0 1-.33-.245a.3.3 0 0 1-.011-.144a.74.74 0 0 0-.038-.379h-.17l-.015.085a1.4 1.4 0 0 0-.004.313a.33.33 0 0 1-.095.256a.35.35 0 0 1-.251.114H4.805a.35.35 0 0 1-.303-.176a.33.33 0 0 1 .014-.345l.152-.237l.985-2.795a.345.345 0 0 1 .331-.227zm-2.003 3.438l.175-.265l1-2.794h.828l.843 2.794l.176.265H6.76a1.2 1.2 0 0 0 0-.34a.8.8 0 0 0-.19-.427h-.577c-.095.11-.133.294-.147.464c-.01.119-.01.228 0 .303zm1.217-1.33l.057.08h.445l.085-.095l-.208-1.032h-.095z");
}

.lvq05bb8c {
  stop-color: var(--svg-color--faf8e4, #faf8e4);
}

.lyfjlhbqd {
  stop-color: var(--svg-color--8e3b09, #8e3b09);
}

.m-7ct7bhz {
  stop-color: var(--svg-color--5b1e11, #5b1e11);
}

.m-lbz7q7r {
  stop-color: var(--svg-color--490802, #490802);
}

.m0c2rsbgh {
  stop-color: var(--svg-color--2f2641, #2f2641);
}

.m6vyslf_u {
  d: path("M11.527 13.469c.014.033.066.095.132.085a.4.4 0 0 0 .1-.033c.056-.02.128-.048.246-.066a.6.6 0 0 1 .374.108l.17-.473l-.27.222c-.321-.047-.51-.014-.757.157z");
}

.mb8s8wqez {
  d: path("M12.412 9.428h.346v2.524h-.346z");
}

.mcusuaboz {
  stop-color: var(--svg-color--e5ab30, #e5ab30);
}

.me09h5d8w {
  stop-color: var(--svg-color--622a11, #622a11);
}

.mgagogbwn {
  stop-color: var(--svg-color--c57e3c, #c57e3c);
}

.mlmu-3b1h {
  stop-color: var(--svg-color--facb66, #facb66);
}

.mn4dmmb2r {
  d: path("m6.61 14.799l-.086.099h.346l.047-.109l-.284-1.104l-.095-.189h-.322l-.123.19l-.331 1.136l.047.076h.27l-.057-.08l.284-1.047h.095z");
}

.mtdxtzbyk {
  fill: var(--svg-color--591812, #591812);
  d: path("m13.705 15.239l-.45.379h.89l-.444-.38zm.133-1.34c-.047.028-.137.142-.137.45h.322v-.095l.966 1.359h.715c-.199-.166-.27-.426-.45-.507a.85.85 0 0 1-.516-.298c-.142-.223-.464-.687-.54-.763a.85.85 0 0 0-.36-.142z");
}

.mw4l2vgpv {
  stop-color: var(--svg-color--f1c870, #f1c870);
}

.mx4euackb {
  stop-color: var(--svg-color--272115, #272115);
}

.mxtp-2bbn {
  stop-color: var(--svg-color--131138, #131138);
}

.n_ypj9blg {
  d: path("M13.724 11.705c.076.066.322.166.521.237v.01h-.63c-.25-.162-.545-.697-.663-.915l-.057-.094q-.022-.028-.066-.034a.3.3 0 0 0-.066 0a1.2 1.2 0 0 0-.35.081v-.109a.9.9 0 0 1 .828.038c.014.024.398.715.483.786");
}

.n0ext-l0k {
  stop-color: var(--svg-color--3b2e59, #3b2e59);
}

.n1trtbwzy {
  stop-color: var(--svg-color--f7eddb, #f7eddb);
}

.n49g6-bec {
  d: path("M10.162 9.428h.417v2.524h-.417z");
}

.n71f3kros {
  stop-color: var(--svg-color--ffdf78, #ffdf78);
}

.n74bractx {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M12.18 14.368h-.658v-.185h.98z");
}

.n7q-3fuez {
  d: path("M8.681 13.094h.346v2.524H8.68z");
}

.n7r3bdbrm {
  stop-color: var(--svg-color--cf8218, #cf8218);
}

.n87nh4jgb {
  stop-color: var(--svg-color--4d311c, #4d311c);
}

.nh45bwbrt {
  stop-color: var(--svg-color--403021, #403021);
}

.nkj9upvut {
  d: path("M7.874 8.675L6.86 7.33c.034-.033.375-.095 1.469-.085c1.103.01 1.747-.166 1.932-.256a18 18 0 0 0 1.397-.73c.119-.094.247-.378.299-.506V8.06l-.014.104c-.01 0-.02.019-.024.038c-.01.023-.024.047-.048.047H8.764c-.483 0-.795.284-.89.426m-.616-1.184l.53.71c.277-.262.643-.41 1.024-.411h2.908a.28.28 0 0 1 .237-.133V7.22l-.408-.303a.36.36 0 0 0-.298.057c0-.047-.028-.142-.147-.095l-.118.057c-.26.133-.834.417-1.492.474a7 7 0 0 1-1.004.004c-.46-.019-.896-.033-1.232.071z");
}

.nklpq44kw {
  stop-color: var(--svg-color--f5c15e, #f5c15e);
}

.nsdyjmb4d {
  stop-color: var(--svg-color--613512, #613512);
}

.nuc_lwbeu {
  stop-color: var(--svg-color--51200f, #51200f);
}

.nv-pjubwm {
  d: path("M5.403 7.287c.222.246.473.781.336 1.468c.095-.204.332-.436.824-.332l1.265.252a20 20 0 0 1-.995-1.355a2.3 2.3 0 0 0-1.17.01a1 1 0 0 1-.26-.043");
}

.nwiyiqbom {
  stop-color: var(--svg-color--f5f4ef, #f5f4ef);
}

.o132jbbtw {
  fill: var(--svg-color--bca98a, #bca98a);
  d: path("M6.391 7.69c-.109.023-.19.142-.213.198c.17-.175.408-.094.507-.038c-.052-.061-.19-.175-.294-.156z");
}

.o9bacs-rg {
  stop-color: var(--svg-color--331b03, #331b03);
}

.oaxs92kcp {
  fill: var(--svg-color--591910, #591910);
  d: path("M11.527 15.24c.071.075.246.231.355.231h.46c.095 0 .317-.17.402-.237h.005l-.208.38h-1.464l.445-.38z");
}

.obq4j4bjn {
  d: path("m16.926 15.58l.36.446c-.014-.18-.01-.635.152-.81h.582c.086.09.242.412.185.81l.379-.445l-.194-.644h-.246l-.038.038h-.692l-.038-.038h-.246l-.199.644z");
}

.oho10q29i {
  stop-color: var(--svg-color--9a4818, #9a4818);
}

.omcvfq02s {
  stop-color: var(--svg-color--3e2a19, #3e2a19);
}

.onhyjw0fx {
  stop-color: var(--svg-color--623209, #623209);
}

.osa178cpr {
  stop-color: var(--svg-color--491f06, #491f06);
}

.otfhg2bbs {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M10.816 10.702h-.63v-.184h.952l-.317.184z");
}

.p_o_qjbrq {
  fill: var(--svg-color--331200, #331200);
  d: path("M3.976 13.492c-.246 0-.417-.356-.469-.521c.36.232.569.118.758.132c.142.01.299.28.355.412c-.393-.303-.331-.023-.644-.023");
}

.p4-21_b4d {
  d: path("M6.79 9.428h.379v2.524H6.79z");
}

.p5fwkxbof {
  stop-color: var(--svg-color--211104, #211104);
}

.p5m98dapk {
  stop-color: var(--svg-color--fef3d7, #fef3d7);
}

.p6hr9gbel {
  d: path("M17.967 8.4c.01-.246.152-.653.223-.828a1.9 1.9 0 0 0-1.052-.048q-.215.322-.369.678c.038.014.663-.142.829-.142c.128 0 .298.222.37.336z");
}

.p6yqf0zgy {
  stop-color: var(--svg-color--632006, #632006);
}

.p72-rqjig {
  d: path("m15.803 13.089l-.11.095l.01 2.43h-.715l-.966-1.365v1.26l.123.104h-.89l.165-.123v-2.254l-.19-.142h.63l1.024 1.501l.066.095h.11v-1.506l-.148-.095zm-1.09.284l-.028-.024a.4.4 0 0 1-.095-.416a.34.34 0 0 1 .322-.223h.89c.143 0 .276.09.328.223a.41.41 0 0 1-.09.407l.01 2.273a.32.32 0 0 1-.1.237a.35.35 0 0 1-.247.104h-.715a.35.35 0 0 1-.284-.142l-.256-.364a.35.35 0 0 1 .024.284a.35.35 0 0 1-.327.222h-.89a.346.346 0 0 1-.337-.427a.33.33 0 0 1 .11-.174l.028-.02v-1.94l-.048-.048c-.113-.09-.151-.28-.104-.412a.35.35 0 0 1 .327-.223h.63c.118 0 .223.057.284.152l.569.871zm-.303 2.022l-.042-.061v.019z");
}

.pb6dk7kbl {
  d: path("m11.527 15.238l-.45.38h1.464l.208-.38h-1.227z");
}

.pfqihubhq {
  stop-color: var(--svg-color--cc9777, #cc9777);
}

.pgmdnyb7w {
  d: path("M10.162 9.8c.02.034.066.096.137.086c.034 0 .062-.014.095-.028c.062-.024.133-.052.251-.067a.55.55 0 0 1 .37.11l.18-.507l-.275.25c-.317-.047-.507-.014-.753.157z");
}

.pijof0a3a {
  stop-color: var(--svg-color--f9e7cd, #f9e7cd);
}

.pptckv-ei {
  d: path("M11.953 7.79v-.133c.132 0 .213.09.236.132h2.909c.516 0 .9.275 1.027.412l.474-.634c.047-.01.118 0 .085.075c-.047.11-.511.659-.544.682c-.015.01-.067-.028-.147-.075c-.157-.095-.408-.251-.635-.275c-.275-.033-2.013-.014-2.842 0h-.284c-.057 0-.114-.057-.16-.104c-.048-.043-.081-.08-.115-.08z");
}

.q2e2p0mtm {
  stop-color: var(--svg-color--392c1c, #392c1c);
}

.q95xftbio {
  stop-color: var(--svg-color--b96833, #b96833);
}

.qblcy-blj {
  stop-color: var(--svg-color--eee6db, #eee6db);
}

.qey2f0bsa {
  stop-color: var(--svg-color--05050c, #05050c);
}

.qf-cthb-b {
  d: path("m11.953 16.235l-.616.388c-.09-.071-.327-.17-.545-.024c-.01.015-.061.034-.17-.038l-.299-.18l-.876-.549l-.1.114l.664.426c.104.725.52 1.54.597 1.54c.317.042 1.022.18 1.35.482v-2.16z");
}

.qkve6ibea {
  stop-color: var(--svg-color--ffef94, #ffef94);
}

.qn9e8c5vo {
  d: path("M13.848 17.532c1.16-1.204 2.178-1.104 3.045-1.104l-1.35-.654l-.767.18l-.654.403c-.047.028-.08.166-.085.218z");
}

.qoujutbnr {
  stop-color: var(--svg-color--f3e7cd, #f3e7cd);
}

.qsfehi76q {
  stop-color: var(--svg-color--fae7a2, #fae7a2);
}

.quc-ljcdf {
  d: path("M12.985 17.02c0 .033.17.08.256.1c.028.047-.124.061-.223.085c-.095.024-.071.085-.123.123c-.048.033-.483.204-.706.36c-.175.128-.142.2-.109.218c.355-.232.924-.265 1.16-.251c.124-.284.365-.853.375-.9c.01-.061-.024-.038-.1-.024c-.076.015-.147.18-.331.157c-.19-.024-.2.094-.2.132");
}

.qvtwi5bex {
  fill: var(--svg-color--221913, #221913);
  d: path("M3.062 8.215c.047.246.161.691.298.833c.235.34.403.721.498 1.123v.047c-.133-.27-.308-.478-.455-.653c-.128-.157-.237-.284-.265-.403a5 5 0 0 1-.076-.947");
}

.rc2htabgw {
  d: path("M10.328 16.83c-.048-.01-.08 0-.052.08c.037.12.213.57.293.744c.01.033.047.11.076.11h.01c.085 0 .644-.015 1.065.227c.062.037.175.033.104-.09a2.24 2.24 0 0 0-1.155-.247c-.095-.227-.275-.649-.341-.824");
}

.rfle-yo8y {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m7.168 9.772l-.445-.378h.89z");
}

.ry9t8br7b {
  d: path("M7.159 16.783v-.014L6.107 12.87c-.942-1.516-.819-2.68-.435-3.855a1.78 1.78 0 0 0-.27-1.73c-.488-.141-1.255-.643-2.103-1.68c.156.421.379.771.616 1.08c.127.165.274.33.426.487c.388.426.777.853.824 1.355c.033.346-.028.705-.095 1.099a8 8 0 0 0-.113.88c-.062.882.473 2.004.753 2.45l.715 1.515l.355 3.898l.379-1.592z");
}

.s5r_dzt0x {
  stop-color: var(--svg-color--4b3424, #4b3424);
}

.s6dnkoxpr {
  stop-color: var(--svg-color--513c21, #513c21);
}

.s9zdhr5-n {
  stop-color: var(--svg-color--4f1c00, #4f1c00);
}

.sb02tqh1r {
  stop-color: var(--svg-color--ca994d, #ca994d);
}

.smaluok0v {
  stop-color: var(--svg-color--6b1b08, #6b1b08);
}

.sq4y3_bfs {
  stop-color: var(--svg-color--5a391a, #5a391a);
}

.sq9oklbmf {
  stop-color: var(--svg-color--d39c56, #d39c56);
  stop-opacity: 0.64;
}

.swa2ezbnk {
  d: path("M11.953 7.79v-.133a.28.28 0 0 0-.232.132H8.813c-.512 0-.9.275-1.023.412l-.474-.634c-.047-.01-.118 0-.085.075c.047.11.506.659.544.682c.015.01.067-.028.142-.075c.157-.095.408-.251.64-.275c.275-.033 2.008-.014 2.842 0h.284c.057 0 .109-.057.16-.104c.043-.043.081-.08.114-.08z");
}

.swssssb7k {
  stop-color: var(--svg-color--8c653c, #8c653c);
}

.sxiw3wbga {
  stop-color: var(--svg-color--352c7d, #352c7d);
}

.t3qm8-2cl {
  fill: var(--svg-color--c4802f, #c4802f);
  d: path("M3.854 10.214c.099-1.165-.521-1.563-.806-2.013c0 .445.062.824.09.962c.067.25.47.544.716 1.051");
}

.t6vlumblz {
  fill: var(--svg-color--4d0206, #4d0206);
  d: path("M5.843 16.149H4.806l.682-.398l.36.398zm.92 0l.378-.398l.687.398z");
}

.t7ysynb7s {
  stop-color: var(--svg-color--8f4a12, #8f4a12);
}

.t8sp6obnr {
  d: path("m16.126 8.202l.53-.71c-.577-.19-1.444 0-2.235-.077c-.796-.075-1.464-.473-1.61-.535c-.119-.047-.147.047-.147.095a.36.36 0 0 0-.299-.057l-.407.303v.436c.128 0 .208.09.237.132h2.903c.516 0 .9.275 1.028.413");
}

.tntj13thg {
  stop-color: var(--svg-color--aa6c33, #aa6c33);
}

.tuefaccdr {
  d: path("M3.144 11.545c.1.095.275.322.44.71c.119.28.327.347.521.323l.01-.01c-.057-.042-.218-.213-.393-.53a1.13 1.13 0 0 0-.597-.512l.014.02z");
}

.twrdk2boi {
  d: path("M13.677 13.09h-.446l.446.379v.01l.16.435c.086.014.28.066.36.142c.076.08.394.54.54.763a.86.86 0 0 0 .512.288c.062-.056.161-.227.161-.492l-.35-.019v.095h-.11l-1.089-1.596h-.19z");
}

.txkv6dzmq {
  stop-color: var(--svg-color--0a0904, #0a0904);
}

.ty9x7ebll {
  stop-color: var(--svg-color--df8338, #df8338);
}

.u-o8pjb3w {
  stop-color: var(--svg-color--d89d1d, #d89d1d);
}

.u2tijnjuy {
  stop-color: var(--svg-color--fbedd0, #fbedd0);
}

.u6h9a_bzi {
  fill: var(--svg-color--19150a, #19150a);
  d: path("M16.595 7.576a5.7 5.7 0 0 0-1.137-.014c-.237.014-.483.033-.867.024a5.6 5.6 0 0 1-1.728-.488l-.114.185l-.308-.185l-.483.332v-.21l.407-.303c.048-.019.17-.028.299.057c0-.048.028-.142.147-.095l.118.057c.26.133.834.417 1.492.474a7 7 0 0 0 1 .004c.463-.019.9-.033 1.235.071l-.066.095z");
}

.u7jua95qs {
  d: path("m7.785 8.202l-.53-.71c.582-.19 1.45 0 2.24-.077c.791-.075 1.459-.473 1.61-.535c.119-.047.147.047.147.095a.36.36 0 0 1 .299-.057l.407.303v.436a.28.28 0 0 0-.237.132H8.813c-.511 0-.9.275-1.023.413z");
}

.ugsx3wbjm {
  stop-color: var(--svg-color--e4af47, #e4af47);
}

.uiqcvnb0o {
  d: path("m6.78 18.37l-.355-3.893l-.715-1.516c-.275-.45-.815-1.572-.758-2.453a9 9 0 0 1 .118-.881c.067-.394.128-.758.095-1.1c-.047-.506-.436-.932-.824-1.354a7 7 0 0 1-.426-.488a4.2 4.2 0 0 1-.616-1.08c.028.356.218 1.076.72 1.895c.094.161.184.289.256.398c.355.545.421.64.303 1.733c-.27 1.573.184 2.373.97 3.77l.086.152l-.147 2.728c.341.45 1.08 1.502 1.288 2.113v-.024z");
}

.umptxtbeu {
  fill: var(--svg-color--fbc56b, #fbc56b);
  d: path("M3.56 10.545a1.4 1.4 0 0 1-.512-.791c-.08.256-.095.871.25 1.137c.246.196.437.452.555.743c0-.227.07-.781-.294-1.09");
}

.unj05t3_y {
  d: path("M9.84 9.428h.322v2.524H9.84z");
}

.uoi61c4tl {
  stop-color: var(--svg-color--faeb96, #faeb96);
}

.upa54prsj {
  stop-color: var(--svg-color--88522e, #88522e);
}

.upcbqqbkl {
  stop-color: var(--svg-color--dc9a1f, #dc9a1f);
}

.uu_y1dr7v {
  d: path("M8.335 13.094h.346v2.524h-.346z");
}

.uuqza_bml {
  stop-color: var(--svg-color--914a2c, #914a2c);
}

.uyukznbpa {
  d: path("m8.68 13.469l-.445-.38h1.222c.393 0 .71.313.71.697c0 .26-.151.488-.37.602h.006l-.237.014c.08-.11.232-.389.203-.644c-.033-.27-.284-.483-.596-.507a.62.62 0 0 0-.493.218");
}

.uz9r4gbrw {
  stop-color: var(--svg-color--f3efee, #f3efee);
}

.v_blhkbvf {
  d: path("M20.857 11.545a2.2 2.2 0 0 0-.44.71c-.12.28-.328.347-.522.323l-.01-.01c.058-.042.219-.213.394-.53c.18-.322.474-.474.597-.512l-.015.02z");
}

.v_ck__bhy {
  stop-color: var(--svg-color--be7234, #be7234);
}

.v_d9vacte {
  stop-color: var(--svg-color--773911, #773911);
}

.v0hbuw06s {
  stop-color: var(--svg-color--ffeea1, #ffeea1);
}

.v2yz1vp5a {
  fill: var(--svg-color--221913, #221913);
  d: path("M20.937 8.215c-.047.246-.16.691-.298.838a3.3 3.3 0 0 0-.497 1.118v.047c.132-.27.308-.478.454-.653c.128-.157.237-.284.265-.403q.082-.47.076-.947");
}

.v8zcg6b8e {
  stop-color: var(--svg-color--662d15, #662d15);
}

.vfa93d36o {
  stop-color: var(--svg-color--d18a20, #d18a20);
}

.vo0bpof5f {
  stop-color: var(--svg-color--412613, #412613);
}

.vpnwt3bic {
  stop-color: var(--svg-color--e2aa79, #e2aa79);
}

.vrniw_foq {
  d: path("M5.947 8.4a3.2 3.2 0 0 0-.222-.828a1.9 1.9 0 0 1 1.051-.048c.133.223.398.668.37.678c-.038.014-.668-.142-.83-.142c-.127 0-.302.222-.369.336z");
}

.vslz9qnoy {
  fill: var(--svg-color--391101, #391101);
  d: path("M19.501 13.87c.308.095.507.038.569 0c-.142.208-.299.308-.408.341c-.094.033-.16-.029-.246-.066c-.128-.048-.204-.048-.251-.048c.133-.241.28-.255.332-.227z");
}

.vu_3racob {
  d: path("M11.522 13.094h.37v2.524h-.37z");
}

.vulazduac {
  d: path("M10.93 17.02c0 .033-.17.08-.26.1c-.024.047.122.061.222.085s.075.085.123.123c.047.033.483.204.71.36c.176.128.143.2.11.218a2.2 2.2 0 0 0-1.166-.251q-.194-.446-.37-.9c-.013-.061.024-.038.096-.024c.075.015.151.18.336.157c.19-.024.199.094.199.132");
}

.vw08jibsn {
  stop-color: var(--svg-color--ffcb7a, #ffcb7a);
}

.w_ns7fs-b {
  stop-color: var(--svg-color--f5f3e7, #f5f3e7);
}

.w1jqanb5f {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M10.816 10.702h-.654v-.184h.976l-.318.184z");
}

.w2aj1ybzn {
  d: path("m7.515 11.866l.1.085h-.886l.061-.047V9.441l-.066-.047h.89l-.094.085v1.014h.71V9.479l-.095-.085h.89l-.099.085v2.387l.095.085h-.88l.094-.085v-.985h-.71v.985zm.346-.644v.464l.014.014l.014-.014v-.464zm.014.886c.09.094.232.128.36.128h.691c.17 0 .36-.062.427-.237c.047-.123.014-.218-.08-.313V9.664a.33.33 0 0 0 .075-.355a.35.35 0 0 0-.322-.223h-.89a.36.36 0 0 0-.261.118a.35.35 0 0 0-.26-.118h-.891a.344.344 0 0 0-.337.411q.021.097.09.167v2.022c-.094.095-.122.19-.075.318c.066.175.25.232.421.232h.692c.128 0 .27-.029.36-.128M7.86 9.664l.014-.014l.014.014v.492H7.86z");
}

.w2h3bbbfx {
  stop-color: var(--svg-color--c7a991, #c7a991);
}

.w6r_bnhhz {
  stop-color: var(--svg-color--a95817, #a95817);
}

.wb2umqb3j {
  d: path("M10.599 17.881a3.7 3.7 0 0 1-.569-1.44v-.004c0-.1 0-.313-.559-.592l-.421.123c.237.113.71.36.743.445c.029.09.171.677.237.962a2.76 2.76 0 0 0-2.984-.962l.076.38l.029.013l.01-.028a3.7 3.7 0 0 1 1.245-.062c.497.076.876.45 1.26.83c.393.383.786.771 1.316.847a3 3 0 0 1-.383-.512");
}

.wbosulbty {
  d: path("m5.487 15.746l.36.402c-.019-.18-.01-.587.147-.762h.583a.95.95 0 0 1 .184.762l.38-.402l-.19-.64H6.7l-.038.034H5.97l-.037-.034h-.247z");
}

.wgzybhqow {
  fill-rule: evenodd;
  d: path("M16.225 11.957h.01c.24-.029.468-.12.662-.265a1.25 1.25 0 0 0 .493-1.16a1.342 1.342 0 0 0-1.753-1.071a1.28 1.28 0 0 0-.9 1.387a1.33 1.33 0 0 0 1.488 1.109m.028-.332q.136.043.209.029l.023-.014a.34.34 0 0 0 .142-.162c.12-.303.128-.638.024-.947a1.32 1.32 0 0 0-.748-.781a.3.3 0 0 0-.17-.01a.3.3 0 0 0-.162.119l-.033.056c-.142.247-.142.678-.038.971a1.3 1.3 0 0 0 .753.74m-.412-1.549a.8.8 0 0 0-.066.318c0 .142.019.284.052.393a.9.9 0 0 0 .502.516v-.005a1.1 1.1 0 0 0-.01-.663a1.1 1.1 0 0 0-.478-.559m1.895.417c.113.872-.55 1.62-1.473 1.729l-.237.014c-.829-.014-1.52-.554-1.63-1.35a1.61 1.61 0 0 1 1.455-1.785a1.677 1.677 0 0 1 1.885 1.392");
}

.wig9qtbgj {
  stop-color: var(--svg-color--e0bfa0, #e0bfa0);
}

.wilor5buq {
  stop-color: var(--svg-color--130a03, #130a03);
}

.wkstusxng {
  fill: var(--svg-color--19150a, #19150a);
  d: path("M7.326 7.576c.53-.056.814-.033 1.132-.014c.236.014.483.033.866.024a5.6 5.6 0 0 0 1.73-.488l.113.185l.308-.185l.483.332v-.21l-.408-.303a.36.36 0 0 0-.298.057c0-.048-.029-.142-.147-.095l-.118.057c-.26.133-.834.417-1.492.474a7 7 0 0 1-1.004.004c-.46-.019-.895-.033-1.232.071l.067.095z");
}

.wsx1dhb8l {
  d: path("M13.586 16.83c.043-.01.08 0 .052.08q-.135.378-.293.744c-.014.033-.048.11-.076.11h-.01c-.085 0-.644-.015-1.07.227c-.057.037-.17.033-.1-.09a2.24 2.24 0 0 1 1.152-.247c.099-.227.279-.649.345-.824");
}

.wzi8kgbcv {
  stop-color: var(--svg-color--ba8342, #ba8342);
}

.x1vbayu6s {
  stop-color: var(--svg-color--efc123, #efc123);
}

.x2jfu5g_c {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M7.17 10.493h1.387v.194H7.17z");
}

.x7emutbbv {
  d: path("m18.048 14.629l-.08.1h.345l.048-.11l-.285-1.103l-.094-.19h-.322l-.123.19l-.332 1.141l.047.071h.27l-.061-.08l.284-1.043h.1z");
}

.x9-wmpnpy {
  stop-color: var(--svg-color--ffe577, #ffe577);
}

.xr1bi6b-r {
  stop-color: var(--svg-color--010508, #010508);
}

.xtpkynb9n {
  stop-color: var(--svg-color--d9d9d9, #d9d9d9);
  stop-opacity: 0;
}

.y_155ubza {
  stop-color: var(--svg-color--501f0c, #501f0c);
}

.y1ioq5bib {
  stop-color: var(--svg-color--ecc276, #ecc276);
}

.y2asf4dnb {
  stop-color: var(--svg-color--d7a44b, #d7a44b);
}

.y7h6b0w5l {
  stop-color: var(--svg-color--755332, #755332);
}

.yb5--h0ey {
  d: path("M10.012 16.367c.284.18.568.332.758.389a.83.83 0 0 1 .53 0l.659-.313v-.208l-.616.388c-.095-.071-.332-.17-.55-.024c-.01.015-.061.034-.17-.038l-.299-.18l-.876-.549l-.08.095c.142.1.331.237.535.37l.114.07z");
}

.yf-3s96du {
  stop-color: var(--svg-color--683b24, #683b24);
}

.ygja7ia_w {
  stop-color: var(--svg-color--090c03, #090c03);
}

.yw_u-7bgn {
  d: path("M16.472 11.777c.407-.114.71-.748.52-1.345c-.198-.602-.89-.947-1.311-.824c-.474.137-.74.753-.545 1.354c.199.602.824.962 1.335.815m.175-1.246c.156.445.047 1.047-.19 1.123c-.16.047-.767-.232-.956-.767c-.143-.394-.086-1.047.236-1.147c.228-.07.74.299.91.791");
}

.z6co51swv {
  d: path("M13.886 17.376c.023-.095-.029.128 0 0a2.76 2.76 0 0 1 2.983-.962v.015h-.16c-.825-.01-1.781-.014-2.861 1.103z");
}

.za1aw8bfm {
  stop-color: var(--svg-color--36271c, #36271c);
}

.zcbo6vbdf {
  stop-color: var(--svg-color--6f4d28, #6f4d28);
}

.zel3fs9co {
  d: path("M5.946 8.4c.071-.081.256-.233.393-.223c.086.005.237.052.38.095c.156.052.307.1.35.09c.07-.024.08-.114.076-.161a2 2 0 0 1-.299-.053c-.199-.042-.44-.094-.53-.094c-.128 0-.303.227-.37.34z");
}

.ziq5t8bhu {
  d: path("M9.025 14.463H9.1c.236.01.393.095.407.123c.01.024.393.71.483.786c.076.066.322.166.512.237l.004.005h-.63c-.25-.156-.544-.692-.663-.914l-.057-.095c-.033-.033-.104-.038-.142-.033a1.2 1.2 0 0 0-.34.085v-.109a.9.9 0 0 1 .345-.085z");
}

.zollgim6s {
  d: path("m12.412 9.772l-.502-.378h1.283c.389 0 .706.34.706.724a.69.69 0 0 1-.365.607h.005l-.237.014c.08-.11.232-.393.199-.645a.65.65 0 0 0-.592-.544c-.19-.014-.365.08-.497.218z");
}

.zy-dyjbcp {
  d: path("M17.967 8.4c-.075-.081-.255-.233-.393-.223c-.085.005-.237.052-.379.095c-.156.052-.308.1-.355.09c-.066-.024-.076-.114-.07-.161c.013.004.141-.02.297-.053c.2-.042.441-.094.531-.094c.128 0 .298.227.37.34z");
}

</style>
