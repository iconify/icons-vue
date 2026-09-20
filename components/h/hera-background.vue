<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGyV7J6bWD)" class="ptw8_fbxn"/><path fill="url(#SVGPCwIwbJW)" class="ordpw7e7g"/><path fill="url(#SVGm687D2oE)" class="s5npxkbyy"/><path fill="url(#SVGXHjW9mjl)" class="eff866b8b"/><path fill="url(#SVGt9e9vcBZ)" class="pm1mcymjg"/><path fill="url(#SVGkM2S14fF)" class="vky08jbfa"/><path fill="url(#SVGWxcqDFyJ)" class="drxi32b6q"/><path class="q6hyxobqu"/><path fill="url(#SVGLwbApdzu)" class="dls45qbov"/><path fill="url(#SVGxXSMBens)" class="tcjcxtbom"/><path class="qaujelb6y"/><path fill="url(#SVG3wEYrdHF)" class="k71604adk"/><path fill="url(#SVGG0vdocAe)" class="s-gv73khp"/><path fill="url(#SVGwGUrQbSY)" class="x97dedk8b"/><path fill="url(#SVGwTZMFeNO)" class="tinlozztt"/><path fill="url(#SVGfNKHCeAe)" class="x31ma4brj"/><path fill="url(#SVG5iW98c6n)" class="b9hip92te"/><path fill="url(#SVGrxsQIbHc)" class="n2y3hbblw"/><path fill="url(#SVGj9UlEcHF)" class="ydq49s4wy"/><path fill="url(#SVGW63pFdlA)" class="qz2h5i9zs"/><path fill="url(#SVGs12BXcub)" class="hlapf6fah"/><path fill="url(#SVGWmsIUc3K)" class="j21-9okgp"/><path fill="url(#SVGO4lhmcdZ)" class="gwt398bbx"/><path fill="url(#SVGDKShHejs)" class="luh5o0bgc"/><path class="t6l0aybgj"/><path fill="url(#SVGI2NiteDM)" class="rmy4mpbca"/><path fill="url(#SVGpkWmrbIF)" class="lngkpvv7j"/><path class="fb_s6lerj"/><path fill="url(#SVG3sblwdjc)" class="vz_g-pbqr"/><path fill="url(#SVGgSgKHbwE)" class="ucxb3w3ji"/><path fill="url(#SVGiX1NrcyF)" class="lshhxwcnk"/><path fill="url(#SVG8ppemcDF)" class="tkeuenk-g"/><path fill="url(#SVGnjpFXdDF)" class="ikko8eb7o"/><path fill="url(#SVGOVhNTdsU)" class="f-w1fdc3m"/><path fill="url(#SVGYXGxJcqh)" class="ufq5i8bws"/><path class="ugjhvwb5d"/><path class="qoc9pykas"/><path class="c6b108bts"/><path class="ixukz_b8h"/><path class="xi2vqyolr"/><path fill="url(#SVGmb9sadZb)" class="i4ug4d5ih"/><path class="winlh2cjr"/><path class="qcrmex6dh"/><path fill="url(#SVGAeVvLcXr)" class="iurj8el_o"/><path class="u6lrxlzxu"/><path class="r8fz4wbpg"/><path class="gkto36b8g"/><path class="jdu7lsbcr"/><path class="f108djb5h"/><path fill="url(#SVGXmu7CdnW)" class="ynsb2_ycx"/><path class="hyu9m5b5s"/><path class="f9suz-ilz"/><path fill="url(#SVGY9kHQTcp)" class="nflo1qbqf"/><path fill="url(#SVG4ODZ3bvf)" class="w0ex36jbj"/><path fill="url(#SVG7zgBNlbK)" class="twneb2sbd"/><path fill="url(#SVG3zFUzevT)" class="x99edrb4i"/><path class="xp4q1n14p"/><path fill="url(#SVGFbY12cwc)" class="hr--b72fa"/><path class="euo3vtb1c"/><path class="bvm45tbbp"/><path fill="url(#SVGTwT73cNB)" class="hw6w9xbhx"/><path class="e5v9uebez"/><path class="gaeugqwgd"/><path class="womd-bbas"/><path fill="url(#SVGQsYrMczw)" class="ukdsjjb4d"/><path fill="url(#SVGNTvLHbLy)" class="l6wookk7q"/><path fill="url(#SVGKh4UKkRK)" class="c4ky9abab"/><path class="f1i64f98s"/><path class="vi-dtpbsz"/><path fill="url(#SVG84y4ebHs)" class="toe9lvbna"/><path class="wm7rzrk8w"/><path fill="url(#SVG2gp2qbTW)" class="mt6f1qb9e"/><path fill="url(#SVGtOalpeEe)" class="ok6xrtbdj"/><path fill="url(#SVG3D0d9b8l)" class="ggud3gb4v"/><path class="zngk21bek"/><path fill="url(#SVGfUxlLTDB)" class="gte_c_h-j"/><path fill="url(#SVGU9hT3y6Q)" class="v2wp01uwu"/><path class="crn3lxben"/><path class="asdjbhdsj"/><path class="inm3ymc5r"/><path fill="url(#SVGze4QVb7t)" class="cdm4fsg_w"/><path fill="url(#SVG34y0J6uk)" class="inp-kpbfu"/><path fill="url(#SVGxmHyCb7F)" class="aa2-_cm0r"/><path fill="url(#SVGEtNFFd2R)" class="q48t9607c"/><path fill="url(#SVGlCANRdqR)" class="ng8osx0km"/><path fill="url(#SVGFVmpYdTp)" class="e-8utxekr"/><path fill="url(#SVGnzxYMe4W)" class="gwpr2mp2u"/><path class="nzaoip1jk"/><path fill="url(#SVGawKWNb2L)" class="xyjh2fa4b"/><path fill="url(#SVGeVldxe2m)" class="qhcwx2b4t"/><path fill="url(#SVGHqifgbRh)" class="j44l1eb4a"/><path fill="url(#SVGLHxexKfx)" class="o3kk6kbma"/><path fill="url(#SVG1sXSpdox)" class="aqw_zvp6c"/><path class="b31p3i7vt"/><path fill="url(#SVGHyVVUd4U)" class="tycvg-stn"/><path fill="url(#SVGfbDEaexw)" clip-rule="evenodd" class="m3yjm0bff"/><path fill="url(#SVGkj0nldiL)" class="udnqcob7n"/><path fill="url(#SVGrZtuzbKI)" clip-rule="evenodd" class="w76h2-b1i"/><path fill="url(#SVGe3IOOc9Y)" class="kbl700itt"/><path fill="url(#SVGtU4XlbHU)" clip-rule="evenodd" class="sfal9o2cv"/><path class="ja0j1zbot"/><path fill="url(#SVGv7qQWcEj)" class="b9cg0abtn"/><path class="w9hsc3n3c"/><path fill="url(#SVGVFIDwe8q)" class="r6r6jgbjf"/><path fill="url(#SVGA6rDZcLc)" class="xrjg-tb9l"/><path fill="url(#SVG5tubce2u)" clip-rule="evenodd" class="ve8bibb9a"/><path class="a38m5fbph"/><path fill="url(#SVGeKVIjcAi)" class="i4xohlb5c"/><path class="bd4gi3-ks"/><path fill="url(#SVG4TCjWlCg)" class="xz1_ucioz"/><path fill="url(#SVGKU6AqcGa)" class="w8ys6zbol"/><path fill="url(#SVGWwbQpdAJ)" class="gns62-m5c"/><path fill="url(#SVGrKmRnelc)" class="boqqgkkot"/><path fill="url(#SVGsLCfmcuX)" class="k8pcdq8-b"/><path class="b63tn200p"/><path class="i0n7gwbqa"/></g><defs><linearGradient id="SVGyV7J6bWD" x1="13.544" x2="13.481" y1="8.56" y2="17.241" gradientUnits="userSpaceOnUse"><stop offset=".11" class="qey2f0bsa"/><stop offset=".23" class="kz2p3vbtw"/><stop offset=".28" class="mxtp-2bbn"/><stop offset=".43" class="sxiw3wbga"/><stop offset=".56" class="hpkmyhb7q"/><stop offset="1" class="xr1bi6b-r"/></linearGradient><linearGradient id="SVGPCwIwbJW" x1="7.508" x2="10.973" y1="16.151" y2="17.59" gradientUnits="userSpaceOnUse"><stop class="p5fwkxbof"/><stop offset=".24" class="swssssb7k"/><stop offset=".41" class="zcbo6vbdf"/><stop offset=".69" class="sq4y3_bfs"/><stop offset="1" class="f80ymbcrs"/></linearGradient><linearGradient id="SVGm687D2oE" x1="4.682" x2="6.96" y1="6.329" y2="17.667" gradientUnits="userSpaceOnUse"><stop class="wzi8kgbcv"/><stop offset=".13" class="y2asf4dnb"/><stop offset=".21" class="iqst3-b8h"/><stop offset=".27" class="mw4l2vgpv"/><stop offset=".39" class="gcglvdbwe"/><stop offset=".51" class="mlmu-3b1h"/><stop offset=".88" class="i981ddbei"/><stop offset="1" class="mgagogbwn"/></linearGradient><linearGradient id="SVGXHjW9mjl" x1="4.552" x2="6.745" y1="6.746" y2="17.397" gradientUnits="userSpaceOnUse"><stop class="za1aw8bfm"/><stop offset=".23" class="doo4m3b4n"/><stop offset=".42" class="vo0bpof5f"/><stop offset=".47" class="j01i7kt2d"/><stop offset=".56" class="osa178cpr"/><stop offset=".89" class="o9bacs-rg"/><stop offset="1" class="p6yqf0zgy"/></linearGradient><linearGradient id="SVGt9e9vcBZ" x1="6.948" x2="7.108" y1="7.773" y2="8.981" gradientUnits="userSpaceOnUse"><stop class="g5w7ob2ex"/><stop offset=".09" class="g5s298-ox"/><stop offset=".75" class="cw5nb2imu"/><stop offset="1" class="dhbelce6q"/></linearGradient><linearGradient id="SVGkM2S14fF" x1="7.053" x2="7.121" y1="7.975" y2="8.527" gradientUnits="userSpaceOnUse"><stop class="wilor5buq"/><stop offset="1" class="nh45bwbrt"/></linearGradient><linearGradient id="SVGWxcqDFyJ" x1="6.649" x2="7.684" y1="8.732" y2="8.698" gradientUnits="userSpaceOnUse"><stop class="jbqp28r_r"/><stop offset="1" class="n71f3kros"/></linearGradient><linearGradient id="SVGLwbApdzu" x1="11.853" x2="7.896" y1="7.815" y2="8.329" gradientUnits="userSpaceOnUse"><stop class="gzjhf9byz"/><stop offset=".33" class="q2e2p0mtm"/><stop offset=".54" class="mx4euackb"/><stop offset="1" class="s6dnkoxpr"/></linearGradient><linearGradient id="SVGxXSMBens" x1="11.852" x2="7.865" y1="7.752" y2="8.422" gradientUnits="userSpaceOnUse"><stop class="bp7n1ix3g"/><stop offset=".19" class="dwuqjgb9m"/><stop offset=".26" class="llfn4bbcd"/><stop offset=".56" class="giv4mpb3a"/><stop offset="1" class="y7h6b0w5l"/></linearGradient><linearGradient id="SVG3wEYrdHF" x1="7.815" x2="11.97" y1="8.27" y2="8.325" gradientUnits="userSpaceOnUse"><stop class="hvj2ivbni"/><stop offset=".32" class="nklpq44kw"/><stop offset=".89" class="uoi61c4tl"/><stop offset="1" class="auvjyvbul"/></linearGradient><linearGradient id="SVGG0vdocAe" x1="8.157" x2="10.031" y1="15.675" y2="16.412" gradientUnits="userSpaceOnUse"><stop class="fmf86dblp"/><stop offset=".61" class="bj_yye5uy"/><stop offset="1" class="dxr67cb9t"/></linearGradient><linearGradient id="SVGwGUrQbSY" x1="8.157" x2="10.03" y1="15.675" y2="16.412" gradientUnits="userSpaceOnUse"><stop class="i2d_x08nq"/><stop offset=".61" class="qkve6ibea"/><stop offset="1" class="x9-wmpnpy"/></linearGradient><linearGradient id="SVGwTZMFeNO" x1="11.478" x2="11.499" y1="15.874" y2="17.697" gradientUnits="userSpaceOnUse"><stop class="cg8076kjv"/><stop offset=".27" class="apfd18jyt"/><stop offset=".58" class="n87nh4jgb"/><stop offset=".83" class="omcvfq02s"/><stop offset="1" class="k_etvt9tm"/></linearGradient><linearGradient id="SVGfNKHCeAe" x1="9.664" x2="11.95" y1="15.516" y2="15.852" gradientUnits="userSpaceOnUse"><stop class="fz3ccrkda"/><stop offset=".34" class="sb02tqh1r"/><stop offset=".5" class="upa54prsj"/><stop offset=".68" class="vw08jibsn"/><stop offset=".81" class="csja5bctb"/><stop offset="1" class="c9as41byb"/></linearGradient><linearGradient id="SVG5iW98c6n" x1="10.653" x2="11.874" y1="16.488" y2="17.141" gradientUnits="userSpaceOnUse"><stop class="txkv6dzmq"/><stop offset=".42" class="k8tldig_q"/><stop offset="1" class="ygja7ia_w"/></linearGradient><linearGradient id="SVGrxsQIbHc" x1="10.501" x2="11.844" y1="16.365" y2="17.317" gradientUnits="userSpaceOnUse"><stop class="giquhabiu"/><stop offset=".36" class="bvj3x_vxm"/><stop offset=".63" class="qsfehi76q"/><stop offset="1" class="ix59hspuj"/></linearGradient><linearGradient id="SVGj9UlEcHF" x1="16.416" x2="12.947" y1="16.151" y2="17.59" gradientUnits="userSpaceOnUse"><stop class="p5fwkxbof"/><stop offset=".24" class="swssssb7k"/><stop offset=".41" class="zcbo6vbdf"/><stop offset=".69" class="sq4y3_bfs"/><stop offset="1" class="f80ymbcrs"/></linearGradient><linearGradient id="SVGW63pFdlA" x1="19.242" x2="16.964" y1="6.329" y2="17.667" gradientUnits="userSpaceOnUse"><stop class="wzi8kgbcv"/><stop offset=".13" class="y2asf4dnb"/><stop offset=".21" class="iqst3-b8h"/><stop offset=".27" class="mw4l2vgpv"/><stop offset=".39" class="gcglvdbwe"/><stop offset=".51" class="mlmu-3b1h"/><stop offset=".88" class="i981ddbei"/><stop offset="1" class="mgagogbwn"/></linearGradient><linearGradient id="SVGs12BXcub" x1="19.372" x2="17.178" y1="6.746" y2="17.397" gradientUnits="userSpaceOnUse"><stop class="za1aw8bfm"/><stop offset=".23" class="doo4m3b4n"/><stop offset=".42" class="vo0bpof5f"/><stop offset=".47" class="j01i7kt2d"/><stop offset=".56" class="osa178cpr"/><stop offset=".89" class="o9bacs-rg"/><stop offset="1" class="p6yqf0zgy"/></linearGradient><linearGradient id="SVGWmsIUc3K" x1="16.976" x2="16.816" y1="7.773" y2="8.981" gradientUnits="userSpaceOnUse"><stop class="g5w7ob2ex"/><stop offset=".09" class="g5s298-ox"/><stop offset=".75" class="cw5nb2imu"/><stop offset="1" class="dhbelce6q"/></linearGradient><linearGradient id="SVGO4lhmcdZ" x1="16.871" x2="16.803" y1="7.975" y2="8.527" gradientUnits="userSpaceOnUse"><stop class="wilor5buq"/><stop offset="1" class="nh45bwbrt"/></linearGradient><linearGradient id="SVGDKShHejs" x1="17.271" x2="16.239" y1="8.732" y2="8.698" gradientUnits="userSpaceOnUse"><stop class="jbqp28r_r"/><stop offset="1" class="n71f3kros"/></linearGradient><linearGradient id="SVGI2NiteDM" x1="12.072" x2="16.029" y1="7.815" y2="8.329" gradientUnits="userSpaceOnUse"><stop class="gzjhf9byz"/><stop offset=".33" class="q2e2p0mtm"/><stop offset=".54" class="mx4euackb"/><stop offset="1" class="s6dnkoxpr"/></linearGradient><linearGradient id="SVGpkWmrbIF" x1="12.072" x2="16.059" y1="7.752" y2="8.422" gradientUnits="userSpaceOnUse"><stop class="bp7n1ix3g"/><stop offset=".19" class="dwuqjgb9m"/><stop offset=".26" class="llfn4bbcd"/><stop offset=".56" class="giv4mpb3a"/><stop offset="1" class="y7h6b0w5l"/></linearGradient><linearGradient id="SVG3sblwdjc" x1="16.105" x2="11.95" y1="8.27" y2="8.325" gradientUnits="userSpaceOnUse"><stop class="hvj2ivbni"/><stop offset=".32" class="nklpq44kw"/><stop offset=".89" class="uoi61c4tl"/><stop offset="1" class="auvjyvbul"/></linearGradient><linearGradient id="SVGgSgKHbwE" x1="15.764" x2="13.895" y1="15.675" y2="16.412" gradientUnits="userSpaceOnUse"><stop class="fmf86dblp"/><stop offset=".61" class="bj_yye5uy"/><stop offset="1" class="dxr67cb9t"/></linearGradient><linearGradient id="SVGiX1NrcyF" x1="15.768" x2="13.895" y1="15.675" y2="16.412" gradientUnits="userSpaceOnUse"><stop class="i2d_x08nq"/><stop offset=".61" class="qkve6ibea"/><stop offset="1" class="x9-wmpnpy"/></linearGradient><linearGradient id="SVG8ppemcDF" x1="12.446" x2="12.425" y1="15.874" y2="17.697" gradientUnits="userSpaceOnUse"><stop class="cg8076kjv"/><stop offset=".27" class="apfd18jyt"/><stop offset=".58" class="n87nh4jgb"/><stop offset=".83" class="omcvfq02s"/><stop offset="1" class="k_etvt9tm"/></linearGradient><linearGradient id="SVGnjpFXdDF" x1="14.261" x2="11.975" y1="15.516" y2="15.852" gradientUnits="userSpaceOnUse"><stop class="fz3ccrkda"/><stop offset=".34" class="sb02tqh1r"/><stop offset=".5" class="upa54prsj"/><stop offset=".68" class="vw08jibsn"/><stop offset=".81" class="csja5bctb"/><stop offset="1" class="c9as41byb"/></linearGradient><linearGradient id="SVGOVhNTdsU" x1="13.271" x2="12.05" y1="16.488" y2="17.141" gradientUnits="userSpaceOnUse"><stop class="txkv6dzmq"/><stop offset=".42" class="k8tldig_q"/><stop offset="1" class="ygja7ia_w"/></linearGradient><linearGradient id="SVGYXGxJcqh" x1="13.423" x2="12.076" y1="16.365" y2="17.317" gradientUnits="userSpaceOnUse"><stop class="giquhabiu"/><stop offset=".36" class="bvj3x_vxm"/><stop offset=".63" class="qsfehi76q"/><stop offset="1" class="ix59hspuj"/></linearGradient><linearGradient id="SVGmb9sadZb" x1="4.166" x2="4.865" y1="11.655" y2="12.531" gradientUnits="userSpaceOnUse"><stop class="oho10q29i"/><stop offset="1" class="ty9x7ebll"/></linearGradient><linearGradient id="SVGAeVvLcXr" x1="4.86" x2="5.647" y1="13.704" y2="13.872" gradientUnits="userSpaceOnUse"><stop class="s9zdhr5-n"/><stop offset=".51" class="h-pf9_bvl"/><stop offset="1" class="tntj13thg"/></linearGradient><linearGradient id="SVGXmu7CdnW" x1="19.834" x2="19.136" y1="11.655" y2="12.531" gradientUnits="userSpaceOnUse"><stop class="oho10q29i"/><stop offset="1" class="ty9x7ebll"/></linearGradient><linearGradient id="SVGY9kHQTcp" x1="19.139" x2="18.352" y1="13.704" y2="13.872" gradientUnits="userSpaceOnUse"><stop class="s9zdhr5-n"/><stop offset=".51" class="h-pf9_bvl"/><stop offset="1" class="tntj13thg"/></linearGradient><linearGradient id="SVG4ODZ3bvf" x1="7.554" x2="7.554" y1="9.962" y2="11.718" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVG7zgBNlbK" x1="7.862" x2="7.862" y1="10.038" y2="11.718" gradientUnits="userSpaceOnUse"><stop offset=".11" class="mcusuaboz"/><stop offset=".26" class="vfa93d36o"/><stop offset=".33" class="y1ioq5bib"/><stop offset=".59" class="nuc_lwbeu"/><stop offset=".67" class="c8mvb_bfp"/><stop offset=".83" class="cpcvynb6m"/><stop offset="1" class="wig9qtbgj"/></linearGradient><linearGradient id="SVG3zFUzevT" x1="9.113" x2="9.113" y1="9.962" y2="11.718" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGFbY12cwc" x1="8.333" x2="8.333" y1="9.41" y2="12.26" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGTwT73cNB" x1="8.805" x2="8.805" y1="10.038" y2="11.718" gradientUnits="userSpaceOnUse"><stop offset=".11" class="mcusuaboz"/><stop offset=".26" class="vfa93d36o"/><stop offset=".33" class="y1ioq5bib"/><stop offset=".37" class="fkpatmanp"/><stop offset=".59" class="nuc_lwbeu"/><stop offset=".67" class="c8mvb_bfp"/><stop offset=".83" class="cpcvynb6m"/><stop offset="1" class="wig9qtbgj"/></linearGradient><linearGradient id="SVGQsYrMczw" x1="10.223" x2="10.223" y1="9.962" y2="11.718" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGNTvLHbLy" x1="10.48" x2="10.48" y1="9.962" y2="11.718" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".04" class="fcd8tuppp"/><stop offset=".08" class="t7ysynb7s"/><stop offset=".14" class="b9h46fxle"/><stop offset=".33" class="bpad70bew"/><stop offset=".39" class="v0hbuw06s"/><stop offset=".42" class="fkpatmanp"/><stop offset=".5" class="legevmbog"/><stop offset=".6" class="y_155ubza"/><stop offset=".67" class="v_ck__bhy"/><stop offset=".88" class="cm_9dvf6b"/><stop offset=".94" class="d0aer9ffr"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGKh4UKkRK" x1="9.97" x2="11.465" y1="11.806" y2="11.705" gradientUnits="userSpaceOnUse"><stop class="w2h3bbbfx"/><stop offset=".33" class="d_lcdobeq"/><stop offset=".55" class="dxo3ddczl"/><stop offset="1" class="qblcy-blj"/></linearGradient><linearGradient id="SVG84y4ebHs" x1="10.712" x2="10.712" y1="9.41" y2="12.269" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVG2gp2qbTW" x1="11.259" x2="10.337" y1="9.844" y2="10.067" gradientUnits="userSpaceOnUse"><stop class="dd24mgbeb"/><stop offset=".53" class="onhyjw0fx"/><stop offset="1" class="w6r_bnhhz"/></linearGradient><linearGradient id="SVGtOalpeEe" x1="11.432" x2="11.432" y1="13.217" y2="14.977" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVG3D0d9b8l" x1="11.743" x2="11.743" y1="13.217" y2="14.977" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".06" class="fcd8tuppp"/><stop offset=".08" class="t7ysynb7s"/><stop offset=".14" class="b9h46fxle"/><stop offset=".33" class="bpad70bew"/><stop offset=".39" class="v0hbuw06s"/><stop offset=".42" class="fkpatmanp"/><stop offset=".5" class="legevmbog"/><stop offset=".6" class="y_155ubza"/><stop offset=".67" class="v_ck__bhy"/><stop offset=".88" class="cm_9dvf6b"/><stop offset=".94" class="d0aer9ffr"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGfUxlLTDB" x1="12.468" x2="11.546" y1="13.099" y2="13.322" gradientUnits="userSpaceOnUse"><stop class="dd24mgbeb"/><stop offset=".53" class="onhyjw0fx"/><stop offset="1" class="w6r_bnhhz"/></linearGradient><linearGradient id="SVGU9hT3y6Q" x1="11.18" x2="12.678" y1="15.064" y2="14.963" gradientUnits="userSpaceOnUse"><stop class="w2h3bbbfx"/><stop offset=".33" class="d_lcdobeq"/><stop offset=".55" class="dxo3ddczl"/><stop offset="1" class="qblcy-blj"/></linearGradient><linearGradient id="SVGze4QVb7t" x1="11.924" x2="11.924" y1="12.669" y2="15.527" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVG34y0J6uk" x1="12.215" x2="12.215" y1="9.962" y2="11.718" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGxmHyCb7F" x1="12.522" x2="12.522" y1="9.895" y2="11.718" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".02" class="nsdyjmb4d"/><stop offset=".14" class="upcbqqbkl"/><stop offset=".44" class="legevmbog"/><stop offset=".52" class="pijof0a3a"/><stop offset=".61" class="v_d9vacte"/><stop offset=".68" class="kwn_yqgrs"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGEtNFFd2R" x1="12.72" x2="13.646" y1="9.844" y2="11.861" gradientUnits="userSpaceOnUse"><stop offset=".02" class="iskb2bugy"/><stop offset=".12" class="yf-3s96du"/><stop offset=".28" class="es0s27ble"/><stop offset=".42" class="djlxzublo"/><stop offset=".52" class="n1trtbwzy"/><stop offset=".57" class="qoujutbnr"/><stop offset="1" class="gdem4kb3r"/></linearGradient><linearGradient id="SVGlCANRdqR" x1="12.446" x2="13.869" y1="11.027" y2="11.982" gradientUnits="userSpaceOnUse"><stop class="bnt2kteaq"/><stop offset=".24" class="l1w6x0byw"/><stop offset="1" class="m-7ct7bhz"/></linearGradient><linearGradient id="SVGFVmpYdTp" x1="12.985" x2="12.985" y1="9.41" y2="12.269" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGnzxYMe4W" x1="12.719" x2="13.275" y1="9.625" y2="10.883" gradientUnits="userSpaceOnUse"><stop class="lvq05bb8c"/><stop offset=".42" class="u2tijnjuy"/><stop offset=".59" class="ugsx3wbjm"/><stop offset=".68" class="doiniybay"/><stop offset="1" class="me09h5d8w"/></linearGradient><linearGradient id="SVGawKWNb2L" x1="8.894" x2="8.894" y1="13.217" y2="14.977" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".5" class="legevmbog"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGeVldxe2m" x1="9.201" x2="9.201" y1="13.217" y2="14.977" gradientUnits="userSpaceOnUse"><stop class="u-o8pjb3w"/><stop offset=".02" class="nsdyjmb4d"/><stop offset=".14" class="upcbqqbkl"/><stop offset=".44" class="legevmbog"/><stop offset=".52" class="pijof0a3a"/><stop offset=".61" class="v_d9vacte"/><stop offset=".68" class="kwn_yqgrs"/><stop offset="1" class="pfqihubhq"/></linearGradient><linearGradient id="SVGHqifgbRh" x1="9.398" x2="10.324" y1="13.099" y2="15.12" gradientUnits="userSpaceOnUse"><stop offset=".02" class="iskb2bugy"/><stop offset=".12" class="yf-3s96du"/><stop offset=".28" class="es0s27ble"/><stop offset=".42" class="djlxzublo"/><stop offset=".52" class="n1trtbwzy"/><stop offset=".57" class="qoujutbnr"/><stop offset="1" class="gdem4kb3r"/></linearGradient><linearGradient id="SVGLHxexKfx" x1="9.124" x2="10.547" y1="14.286" y2="15.238" gradientUnits="userSpaceOnUse"><stop class="bnt2kteaq"/><stop offset=".24" class="l1w6x0byw"/><stop offset="1" class="m-7ct7bhz"/></linearGradient><linearGradient id="SVG1sXSpdox" x1="9.398" x2="9.954" y1="12.885" y2="14.143" gradientUnits="userSpaceOnUse"><stop class="lvq05bb8c"/><stop offset=".42" class="u2tijnjuy"/><stop offset=".59" class="ugsx3wbjm"/><stop offset=".68" class="doiniybay"/><stop offset="1" class="me09h5d8w"/></linearGradient><linearGradient id="SVGHyVVUd4U" x1="9.664" x2="9.664" y1="12.669" y2="15.527" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGfbDEaexw" x1="15.183" x2="15.949" y1="9.811" y2="11.895" gradientUnits="userSpaceOnUse"><stop class="p5m98dapk"/><stop offset=".23" class="jkuzdybta"/><stop offset=".42" class="f7_frubvi"/><stop offset=".51" class="ba079nbws"/><stop offset=".6" class="fg0b1x82v"/><stop offset="1" class="cfi1cgbzd"/></linearGradient><linearGradient id="SVGkj0nldiL" x1="15.394" x2="15.87" y1="9.979" y2="11.768" gradientUnits="userSpaceOnUse"><stop class="s5r_dzt0x"/><stop offset=".36" class="v8zcg6b8e"/><stop offset=".69" class="vpnwt3bic"/><stop offset="1" class="uz9r4gbrw"/></linearGradient><linearGradient id="SVGrZtuzbKI" x1="14.896" x2="15.991" y1="9.579" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="effhzw9kj"/><stop offset=".28" class="c_87yqnay"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGe3IOOc9Y" x1="6.947" x2="6.947" y1="12.669" y2="16.003" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGtU4XlbHU" x1="6.948" x2="6.957" y1="12.973" y2="15.432" gradientUnits="userSpaceOnUse"><stop class="x1vbayu6s"/><stop offset=".61" class="i2cxjvv_o"/><stop offset="1" class="id43-44sc"/></linearGradient><linearGradient id="SVGv7qQWcEj" x1="6.969" x2="6.948" y1="13.326" y2="14.589" gradientUnits="userSpaceOnUse"><stop class="l7saelavo"/><stop offset=".19" class="elng2sc5z"/><stop offset=".4" class="lyfjlhbqd"/><stop offset=".93" class="smaluok0v"/><stop offset="1" class="d9hp-_brl"/></linearGradient><linearGradient id="SVGVFIDwe8q" x1="6.872" x2="6.88" y1="14.846" y2="15.688" gradientUnits="userSpaceOnUse"><stop class="m-lbz7q7r"/><stop offset=".43" class="j6nbot4je"/><stop offset="1" class="uuqza_bml"/></linearGradient><linearGradient id="SVGA6rDZcLc" x1="17.12" x2="17.12" y1="12.518" y2="15.852" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVG5tubce2u" x1="17.12" x2="17.129" y1="12.82" y2="15.279" gradientUnits="userSpaceOnUse"><stop class="x1vbayu6s"/><stop offset=".61" class="i2cxjvv_o"/><stop offset="1" class="id43-44sc"/></linearGradient><linearGradient id="SVGeKVIjcAi" x1="17.14" x2="17.119" y1="13.174" y2="14.438" gradientUnits="userSpaceOnUse"><stop class="l7saelavo"/><stop offset=".19" class="elng2sc5z"/><stop offset=".4" class="lyfjlhbqd"/><stop offset=".93" class="smaluok0v"/><stop offset="1" class="d9hp-_brl"/></linearGradient><linearGradient id="SVG4TCjWlCg" x1="17.04" x2="17.048" y1="14.695" y2="15.537" gradientUnits="userSpaceOnUse"><stop class="m-lbz7q7r"/><stop offset=".43" class="j6nbot4je"/><stop offset="1" class="uuqza_bml"/></linearGradient><linearGradient id="SVGKU6AqcGa" x1="14.235" x2="14.235" y1="12.669" y2="15.527" gradientUnits="userSpaceOnUse"><stop class="kmmdfcbdu"/><stop offset=".1" class="n0ext-l0k"/><stop offset=".41" class="a-y59khlr"/><stop offset=".56" class="m0c2rsbgh"/><stop offset="1" class="l9h1mqb9i"/></linearGradient><linearGradient id="SVGWwbQpdAJ" x1="14.269" x2="14.269" y1="12.973" y2="15.204" gradientUnits="userSpaceOnUse"><stop class="b617qxbmc"/><stop offset=".43" class="e5s14nblj"/><stop offset=".5" class="f2a3hrbti"/><stop offset=".54" class="dh3gfdb2p"/><stop offset=".83" class="q95xftbio"/><stop offset="1" class="ig-b6tpfw"/></linearGradient><linearGradient id="SVGrKmRnelc" x1="14.875" x2="14.875" y1="12.973" y2="14.969" gradientUnits="userSpaceOnUse"><stop class="n7r3bdbrm"/><stop offset=".4" class="a18pqob7l"/><stop offset=".62" class="sq9oklbmf"/><stop offset=".67" class="w_ns7fs-b"/><stop offset="1" class="xtpkynb9n"/></linearGradient><linearGradient id="SVGsLCfmcuX" x1="13.389" x2="14.779" y1="13.023" y2="14.682" gradientUnits="userSpaceOnUse"><stop class="fnevu203c"/><stop offset=".12" class="anp4xbbxy"/><stop offset="1" class="nwiyiqbom"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hera-background" /></template>
<style>
.a-y59khlr {
  stop-color: var(--svg-color--3f354e, #3f354e);
}

.a18pqob7l {
  stop-color: var(--svg-color--d17811, #d17811);
}

.a38m5fbph {
  fill: var(--svg-color--faf3d9, #faf3d9);
  d: path("m16.821 12.82l.21.354h.287l.236-.354z");
}

.aa2-_cm0r {
  d: path("M12.366 9.714h.308v2.244h-.308z");
}

.anp4xbbxy {
  stop-color: var(--svg-color--f1d361, #f1d361);
}

.apfd18jyt {
  stop-color: var(--svg-color--624025, #624025);
}

.aqw_zvp6c {
  d: path("m9.05 13.306l-.397-.337H9.74c.35 0 .632.278.632.619a.61.61 0 0 1-.328.534h.004l-.21.013c.07-.097.206-.345.18-.573c-.03-.24-.252-.43-.53-.45a.55.55 0 0 0-.438.194");
}

.asdjbhdsj {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M12.16 14.105h-.585v-.165h.872z");
}

.auvjyvbul {
  stop-color: var(--svg-color--c9a454, #c9a454);
}

.b31p3i7vt {
  fill: var(--svg-color--591812, #591812);
  d: path("m9.05 14.879l-.397.337h.792z");
}

.b617qxbmc {
  stop-color: var(--svg-color--cd7b0f, #cd7b0f);
}

.b63tn200p {
  fill: var(--svg-color--591812, #591812);
  d: path("m13.516 14.879l-.4.337h.791l-.395-.337zm.118-1.191c-.043.025-.122.126-.122.4h.286v-.085l.859 1.208h.635c-.176-.147-.24-.378-.4-.45a.76.76 0 0 1-.458-.265c-.127-.198-.413-.61-.48-.678a.76.76 0 0 0-.32-.126z");
}

.b9cg0abtn {
  d: path("m7.209 14.488l-.076.088h.307l.042-.097l-.252-.98l-.084-.169h-.287l-.11.168l-.294 1.01l.042.068h.24l-.05-.071l.252-.93h.084z");
}

.b9h46fxle {
  stop-color: var(--svg-color--d49522, #d49522);
}

.b9hip92te {
  d: path("M11.049 16.463c0 .03-.152.071-.232.088c-.021.042.11.055.198.076s.067.076.11.11c.041.029.429.18.63.32c.156.113.127.176.097.193a1.97 1.97 0 0 0-1.035-.223a20 20 0 0 1-.328-.8c-.013-.055.02-.034.084-.02c.067.012.134.159.299.138c.168-.021.177.084.177.118");
}

.ba079nbws {
  stop-color: var(--svg-color--a85c20, #a85c20);
}

.bd4gi3-ks {
  fill: var(--svg-color--4d0206, #4d0206);
  d: path("M16.7 15.578h-.923l.607-.395zm.816 0l.337-.395l.606.395z");
}

.bj_yye5uy {
  stop-color: var(--svg-color--3f3124, #3f3124);
}

.bnt2kteaq {
  stop-color: var(--svg-color--844210, #844210);
}

.boqqgkkot {
  d: path("M14.72 12.969h.311v2h-.311z");
}

.bp7n1ix3g {
  stop-color: var(--svg-color--644624, #644624);
}

.bpad70bew {
  stop-color: var(--svg-color--cd8a2a, #cd8a2a);
}

.bvj3x_vxm {
  stop-color: var(--svg-color--efb15f, #efb15f);
}

.bvm45tbbp {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m7.705 10.02l-.395-.336h.79z");
}

.c_87yqnay {
  stop-color: var(--svg-color--4f476f, #4f476f);
}

.c4ky9abab {
  d: path("m10.366 11.621l-.396.337h1.297l.19-.337z");
}

.c6b108bts {
  fill: var(--svg-color--fbc56b, #fbc56b);
  d: path("M4.497 10.707a1.25 1.25 0 0 1-.455-.703c-.071.227-.084.774.223 1.01c.219.175.388.402.493.661c0-.202.063-.694-.261-.968");
}

.c8mvb_bfp {
  stop-color: var(--svg-color--bd6f2f, #bd6f2f);
}

.c9as41byb {
  stop-color: var(--svg-color--885532, #885532);
}

.cdm4fsg_w {
  d: path("M11.907 13.94v-.631a1 1 0 0 1 .143-.017q.086 0 .165.034a.6.6 0 0 1 .122.063l.151-.421h-1.305l.11.097v2.054l-.114.093h1.3l.186-.337h-.758v-.61h.085a.4.4 0 0 1 .151.025l.072.03l.231-.38zm.463.636h.295c.11 0 .21.059.265.147a.3.3 0 0 1 .005.3l-.186.336a.3.3 0 0 1-.27.156h-1.3a.308.308 0 0 1-.3-.38a.3.3 0 0 1 .098-.155h.004V13.2a.36.36 0 0 1-.088-.371a.31.31 0 0 1 .286-.198h1.31c.1 0 .193.046.252.126a.38.38 0 0 1 .038.316l-.156.42a.3.3 0 0 1-.122.152a.28.28 0 0 1 .21.148a.3.3 0 0 1 0 .303l-.231.379a.3.3 0 0 1-.105.1z");
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

.crn3lxben {
  fill: var(--svg-color--591910, #591910);
  d: path("M11.58 14.88c.063.067.219.205.315.205h.409c.084 0 .282-.151.358-.21h.004l-.185.337H11.18l.395-.337z");
}

.csja5bctb {
  stop-color: var(--svg-color--8c5d33, #8c5d33);
}

.cw5nb2imu {
  stop-color: var(--svg-color--69380f, #69380f);
}

.d_lcdobeq {
  stop-color: var(--svg-color--ffeccf, #ffeccf);
}

.d0aer9ffr {
  stop-color: var(--svg-color--ffedd4, #ffedd4);
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

.djlxzublo {
  stop-color: var(--svg-color--fff8f6, #fff8f6);
}

.dls45qbov {
  d: path("m8.254 8.624l-.472-.632c.518-.168 1.288 0 1.992-.067c.703-.068 1.296-.421 1.43-.476c.106-.042.131.042.131.084a.32.32 0 0 1 .266-.05l.362.27v.386a.25.25 0 0 0-.21.118H9.166c-.454 0-.8.244-.909.367z");
}

.doiniybay {
  stop-color: var(--svg-color--612711, #612711);
}

.doo4m3b4n {
  stop-color: var(--svg-color--3b2a1a, #3b2a1a);
}

.drxi32b6q {
  d: path("M6.62 8.8c.062-.072.226-.207.349-.198c.075.004.21.046.336.084c.14.046.274.088.312.08c.063-.021.071-.101.067-.143a2 2 0 0 1-.265-.047c-.177-.037-.391-.084-.471-.084c-.114 0-.27.202-.329.303z");
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

.e-8utxekr {
  d: path("M11.684 9.608a.31.31 0 0 1 .286-.198h1.09a.927.927 0 0 1 .935.918a.9.9 0 0 1-.26.631c.15.354.378.67.492.8c.084.093.097.169.046.274a.31.31 0 0 1-.278.177h-.56a.3.3 0 0 1-.168-.046c-.072-.047-.143-.064-.207-.13l-.008.029c-.042.117-.16.147-.286.147h-.796a.31.31 0 0 1-.286-.198c-.042-.11-.013-.185.067-.265V9.924a.3.3 0 0 1-.067-.316m.286.105l.03.021v2.198l-.03.025h.796l-.088-.075v-.851h.046c.017 0 .033.008.046.013l.025.02l.042.08h.005l.143.253c.126.21.294.463.45.564h.56v-.004a3.5 3.5 0 0 1-.614-1.065c-.009-.004-.009-.012-.013-.021a.63.63 0 0 0 .32-.539a.624.624 0 0 0-.627-.614h-1.09zm.707.245v.9a.35.35 0 0 0 .308-.172a.54.54 0 0 0 .063-.261a.7.7 0 0 0-.063-.295a.34.34 0 0 0-.307-.168z");
}

.e5s14nblj {
  stop-color: var(--svg-color--c1660f, #c1660f);
}

.e5v9uebez {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m8.96 10.02l-.396-.336h.792z");
}

.eff866b8b {
  d: path("m7.36 17.662l-.316-3.46l-.635-1.348c-.245-.4-.725-1.397-.674-2.18a8 8 0 0 1 .105-.783c.06-.35.114-.674.084-.977c-.042-.45-.387-.83-.732-1.204a6 6 0 0 1-.38-.434a3.7 3.7 0 0 1-.546-.96c.025.316.193.956.64 1.684c.084.144.164.257.227.354c.316.484.375.568.27 1.541c-.24 1.398.164 2.11.862 3.351l.076.135l-.13 2.425c.303.4.96 1.334 1.145 1.877v-.02z");
}

.effhzw9kj {
  stop-color: var(--svg-color--877fa4, #877fa4);
}

.elng2sc5z {
  stop-color: var(--svg-color--4b1b05, #4b1b05);
}

.es0s27ble {
  stop-color: var(--svg-color--e3ab3e, #e3ab3e);
}

.euo3vtb1c {
  fill: var(--svg-color--591812, #591812);
  d: path("m7.705 11.621l-.395.337h.79z");
}

.f-w1fdc3m {
  d: path("M12.875 16.463c0 .03.152.071.228.088c.025.042-.11.055-.198.076c-.084.021-.063.076-.11.11c-.042.029-.429.18-.627.32c-.156.113-.126.176-.097.193c.316-.206.821-.236 1.032-.223c.11-.253.324-.758.332-.8c.009-.055-.02-.034-.088-.02c-.067.012-.13.159-.295.138c-.168-.021-.177.084-.177.118");
}

.f108djb5h {
  fill: var(--svg-color--2d0700, #2d0700);
  d: path("M19.359 12.034c.16-.286.42-.421.53-.455c-.1.097-.055.303-.244.745c-.156.37-.505.278-.636.181c.05-.038.194-.19.35-.471");
}

.f1i64f98s {
  fill: var(--svg-color--591910, #591910);
  d: path("M10.366 11.621c.067.072.223.206.32.206h.408c.085 0 .282-.147.354-.206h.008l-.19.337H9.97z");
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

.f9suz-ilz {
  fill: var(--svg-color--391101, #391101);
  d: path("M18.668 13.662c.273.084.45.033.505 0c-.126.185-.266.273-.362.303c-.084.03-.143-.025-.22-.06c-.113-.041-.18-.041-.222-.041c.118-.215.248-.228.294-.202z");
}

.fb_s6lerj {
  fill: var(--svg-color--19150a, #19150a);
  d: path("M16.084 8.068a5 5 0 0 0-1.01-.013c-.21.013-.43.03-.77.021a5 5 0 0 1-1.537-.433l-.101.164l-.274-.164l-.43.294v-.185l.363-.27a.31.31 0 0 1 .265.051c0-.042.025-.126.13-.084l.105.05c.232.118.742.371 1.327.422c.294.029.598.016.888.004c.413-.017.8-.03 1.099.063l-.06.084z");
}

.fcd8tuppp {
  stop-color: var(--svg-color--6e390c, #6e390c);
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

.ft5dv1b6b {
  fill: none;
}

.fz3ccrkda {
  stop-color: var(--svg-color--746b44, #746b44);
}

.g5s298-ox {
  stop-color: var(--svg-color--52371a, #52371a);
}

.g5w7ob2ex {
  stop-color: var(--svg-color--8d6029, #8d6029);
}

.gaeugqwgd {
  fill: var(--svg-color--591812, #591812);
  d: path("m8.96 11.621l-.396.337h.792z");
}

.gcglvdbwe {
  stop-color: var(--svg-color--efcf72, #efcf72);
}

.gdem4kb3r {
  stop-color: var(--svg-color--f0ece9, #f0ece9);
}

.ggud3gb4v {
  d: path("M11.575 12.973h.329v2.244h-.329z");
}

.giquhabiu {
  stop-color: var(--svg-color--be8542, #be8542);
}

.giv4mpb3a {
  stop-color: var(--svg-color--d9913c, #d9913c);
}

.gkto36b8g {
  fill: var(--svg-color--fbc56b, #fbc56b);
  d: path("M19.502 10.707c.227-.175.388-.424.454-.703c.072.227.085.774-.223 1.01a1.6 1.6 0 0 0-.492.661c0-.202-.063-.694.26-.968");
}

.gns62-m5c {
  d: path("m14.623 14.4l-.968-1.431h-.392V15.2h.535V14l.859 1.213h.711v-2.24h-.648V14.4z");
}

.gte_c_h-j {
  d: path("M11.58 13.306c.012.029.058.084.117.075a.4.4 0 0 0 .089-.03c.05-.016.113-.041.219-.058a.52.52 0 0 1 .332.097l.152-.421l-.24.198c-.287-.042-.455-.013-.674.139z");
}

.gwpr2mp2u {
  d: path("m12.366 10.02l-.447-.336h1.141c.346 0 .628.303.628.644c0 .231-.13.433-.325.539h.005l-.21.012c.07-.097.206-.35.176-.572a.576.576 0 0 0-.526-.484a.57.57 0 0 0-.442.193z");
}

.gwt398bbx {
  d: path("M17.304 8.8c.009-.219.135-.58.198-.736a1.7 1.7 0 0 0-.934-.043q-.192.286-.329.603c.034.012.59-.127.737-.127c.114 0 .265.198.328.3z");
}

.gzjhf9byz {
  stop-color: var(--svg-color--3f3126, #3f3126);
}

.h-pf9_bvl {
  stop-color: var(--svg-color--53250d, #53250d);
}

.hlapf6fah {
  d: path("m16.564 17.662l.311-3.46l.64-1.348c.244-.4.724-1.397.674-2.18c-.022-.278-.068-.539-.106-.783A4 4 0 0 1 18 8.914c.042-.45.387-.83.733-1.204c.13-.143.265-.286.378-.434c.211-.273.409-.59.548-.96A4.2 4.2 0 0 1 19.019 8l-.227.354c-.32.484-.375.568-.27 1.541c.236 1.398-.164 2.11-.867 3.351l-.076.135l.135 2.425c-.308.4-.96 1.334-1.145 1.877z");
}

.hpkmyhb7q {
  stop-color: var(--svg-color--14122a, #14122a);
}

.hr--b72fa {
  d: path("m8.013 11.882l.089.075h-.788l.055-.042v-2.19l-.059-.041h.792l-.085.076v.9h.632v-.9l-.084-.076h.791l-.088.076v2.122l.084.075H8.57l.084-.075v-.876h-.631v.876zm.308-.573v.413l.012.012l.013-.012v-.413zm.012.787c.08.084.207.114.32.114h.615c.151 0 .32-.055.379-.21c.042-.11.012-.194-.072-.278V9.924a.3.3 0 0 0 .068-.316a.31.31 0 0 0-.287-.198h-.791a.32.32 0 0 0-.232.105a.3.3 0 0 0-.231-.105H7.31a.306.306 0 0 0-.3.366q.019.085.081.148v1.798c-.084.084-.11.168-.067.282c.059.155.223.206.375.206h.614c.114 0 .24-.025.32-.114m-.012-2.172l.012-.013l.013.013v.438H8.32z");
}

.hvj2ivbni {
  stop-color: var(--svg-color--fff3a7, #fff3a7);
}

.hw6w9xbhx {
  d: path("M8.633 9.714h.307v2.244h-.307z");
}

.hyu9m5b5s {
  fill: var(--svg-color--331200, #331200);
  d: path("M19.132 13.326c.22 0 .37-.315.417-.463c-.32.207-.505.106-.674.118c-.126.008-.265.248-.315.366c.349-.27.294-.02.572-.02");
}

.i0n7gwbqa {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m15.04 13.306l-.45-.337h.846z");
}

.i2cxjvv_o {
  stop-color: var(--svg-color--f6f5f1, #f6f5f1);
}

.i2d_x08nq {
  stop-color: var(--svg-color--b78643, #b78643);
}

.i4ug4d5ih {
  d: path("M4.128 11.596c.089.084.244.286.392.631c.105.249.29.308.463.287l.008-.009c-.05-.038-.193-.19-.35-.471a1 1 0 0 0-.53-.455l.013.017z");
}

.i4xohlb5c {
  d: path("m17.376 14.336l-.072.089h.308l.042-.097l-.253-.98l-.084-.17h-.286l-.11.17l-.294 1.014l.042.063h.24l-.055-.072l.252-.926h.089z");
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

.ikko8eb7o {
  d: path("M13.684 15.882c-.244.16-.496.295-.665.345a.7.7 0 0 0-.476 0l-.58-.278v-.185l.547.345c.084-.063.295-.151.484-.02c.013.012.059.029.156-.034q.52-.327 1.044-.649l.071.085c-.126.088-.294.21-.48.328l-.096.063z");
}

.inm3ymc5r {
  fill: var(--svg-color--501f0c, #501f0c);
  d: path("m12.21 14.315l.237-.375l-.287.152h-.585v.173h.421q.076 0 .147.025l.072.03z");
}

.inp-kpbfu {
  d: path("M12 9.714h.366v2.244H12z");
}

.iqst3-b8h {
  stop-color: var(--svg-color--fdefd2, #fdefd2);
}

.iskb2bugy {
  stop-color: var(--svg-color--60340f, #60340f);
}

.iurj8el_o {
  d: path("M4.826 13.662c.076.071.24.177.43.168c.143 0 .26.009.362.034h.012c-.118-.215-.248-.228-.299-.202c-.273.084-.45.033-.505 0");
}

.ix59hspuj {
  stop-color: var(--svg-color--f8c166, #f8c166);
}

.ixukz_b8h {
  fill: var(--svg-color--30120a, #30120a);
  d: path("M4.042 10.008c0 .202.076.619.367.9c.244.245.324.548.336.742a1.6 1.6 0 0 0-.48-.632c-.307-.24-.294-.783-.223-1.01");
}

.j01i7kt2d {
  stop-color: var(--svg-color--54250b, #54250b);
}

.j21-9okgp {
  d: path("M17.788 7.811c-.197.219-.42.695-.303 1.305c-.08-.18-.29-.387-.728-.295l-1.124.224c.202-.257.652-.842.884-1.204a2 2 0 0 1 1.04.008a1 1 0 0 0 .231-.038");
}

.j44l1eb4a {
  d: path("m9.84 14.135l.21-.009c.143.393.352.76.62 1.082c-.17-.063-.388-.152-.456-.21c-.08-.063-.42-.678-.43-.7c-.012-.02-.155-.096-.361-.109a.8.8 0 0 0-.379.076v-.152h.311c.253 0 .375-.21.375-.429c0-.223-.122-.434-.379-.434c-.084 0-.24.038-.303.055c.114-.122.27-.21.438-.194c.282.021.501.211.53.455c.026.223-.109.472-.176.568");
}

.j6nbot4je {
  stop-color: var(--svg-color--591700, #591700);
}

.ja0j1zbot {
  fill: var(--svg-color--faf3d9, #faf3d9);
  d: path("m6.654 12.969l.206.358h.286l.24-.354H6.65z");
}

.jbqp28r_r {
  stop-color: var(--svg-color--ebb53b, #ebb53b);
}

.jdu7lsbcr {
  fill: var(--svg-color--30120a, #30120a);
  d: path("M19.958 10.008a1.35 1.35 0 0 1-.366.9c-.197.2-.316.463-.337.742c.059-.14.194-.405.48-.632c.307-.24.294-.783.223-1.01");
}

.jkuzdybta {
  stop-color: var(--svg-color--f3d49b, #f3d49b);
}

.k_etvt9tm {
  stop-color: var(--svg-color--873915, #873915);
}

.k71604adk {
  d: path("M11.958 8.257V8.14a.25.25 0 0 0-.207.118H9.168c-.455 0-.8.244-.91.366l-.42-.564c-.043-.008-.106 0-.076.068c.042.097.45.585.484.606c.012.008.059-.025.126-.067c.139-.085.362-.224.568-.245c.244-.03 1.785-.012 2.526 0h.253c.05 0 .097-.05.143-.092c.038-.038.072-.072.101-.072z");
}

.k8pcdq8-b {
  d: path("M13.49 12.969h-.395l.395.337v.008l.143.387c.076.013.249.06.32.127c.068.071.35.48.48.677c.05.068.211.215.455.257c.055-.05.143-.202.143-.438l-.311-.016v.084h-.097l-.968-1.419h-.169z");
}

.k8tldig_q {
  stop-color: var(--svg-color--372f22, #372f22);
}

.kbl700itt {
  d: path("M7.385 12.63a.3.3 0 0 1 .295.216l.737 2.48l.13.201a.29.29 0 0 1 .013.308a.31.31 0 0 1-.27.155h-.947a.31.31 0 0 1-.294-.217a.3.3 0 0 1-.009-.128a.66.66 0 0 0-.034-.337h-.151l-.013.076c-.012.105-.012.21-.004.278a.3.3 0 0 1-.084.227a.3.3 0 0 1-.223.102h-.926a.31.31 0 0 1-.27-.156a.3.3 0 0 1 .013-.308l.134-.21l.876-2.484a.31.31 0 0 1 .295-.202zm-1.78 3.057l.155-.235l.889-2.484h.736l.75 2.484l.156.235h-.948c.017-.113.013-.21 0-.303a.73.73 0 0 0-.168-.379H6.66c-.084.097-.118.261-.13.413a1.4 1.4 0 0 0 0 .27zm1.081-1.183l.051.072h.396l.076-.084l-.186-.918H6.94z");
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

.l6wookk7q {
  d: path("M10.366 9.714h.37v2.244h-.37z");
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

.llfn4bbcd {
  stop-color: var(--svg-color--f6e497, #f6e497);
}

.lngkpvv7j {
  d: path("m15.591 9.045l.901-1.196c-.03-.03-.332-.084-1.305-.076c-.98.009-1.557-.147-1.717-.227a16 16 0 0 1-1.243-.648c-.109-.084-.223-.337-.265-.45v2.05l.009.092c.012 0 .02.017.025.034c.008.02.017.042.042.042H14.8c.43 0 .707.253.791.379m.548-1.053l-.472.632a1.33 1.33 0 0 0-.913-.366h-2.585a.25.25 0 0 0-.211-.118v-.388l.366-.27a.32.32 0 0 1 .265.051c0-.042.026-.126.131-.084l.105.05c.232.119.741.371 1.327.422c.294.03.597.017.888.004c.412-.017.8-.03 1.099.063z");
}

.lshhxwcnk {
  d: path("M13.676 16.779c.02-.085-.026.113 0 0a2.45 2.45 0 0 1 2.652-.855v.013h-.143c-.733-.009-1.583-.013-2.543.98z");
}

.luh5o0bgc {
  d: path("M17.304 8.8c-.067-.072-.227-.207-.349-.198c-.076.004-.21.046-.337.084c-.139.046-.274.088-.316.08c-.058-.021-.067-.101-.063-.143a2 2 0 0 0 .265-.047c.177-.037.392-.084.472-.084c.114 0 .265.202.328.303z");
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

.m3yjm0bff {
  fill-rule: evenodd;
  d: path("M15.764 11.959a1.14 1.14 0 0 0 1.027-1.264a1.19 1.19 0 0 0-1.33-1.002a1.154 1.154 0 0 0-1.024 1.28a1.183 1.183 0 0 0 1.327.99zm.202-.266c.206-.067.303-.602.168-.998c-.156-.437-.61-.766-.817-.703c-.282.084-.328.67-.206 1.02c.168.475.707.723.855.681");
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

.mt6f1qb9e {
  d: path("M10.366 10.046c.017.03.06.084.122.075c.03 0 .055-.012.085-.025c.054-.02.117-.046.223-.059a.5.5 0 0 1 .328.097l.16-.45l-.244.223c-.282-.042-.45-.013-.67.139z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
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

.n0ext-l0k {
  stop-color: var(--svg-color--3b2e59, #3b2e59);
}

.n1trtbwzy {
  stop-color: var(--svg-color--f7eddb, #f7eddb);
}

.n2y3hbblw {
  d: path("M10.514 16.294c-.042-.009-.072 0-.047.071c.034.105.19.506.261.661c.009.03.042.097.068.097h.008c.076 0 .573-.013.947.202c.055.034.156.03.093-.08a2 2 0 0 0-1.027-.219c-.084-.202-.245-.577-.303-.732");
}

.n71f3kros {
  stop-color: var(--svg-color--ffdf78, #ffdf78);
}

.n7r3bdbrm {
  stop-color: var(--svg-color--cf8218, #cf8218);
}

.n87nh4jgb {
  stop-color: var(--svg-color--4d311c, #4d311c);
}

.nflo1qbqf {
  d: path("M19.173 13.662a.62.62 0 0 1-.43.168c-.143 0-.26.009-.362.034h-.012c.118-.215.248-.228.294-.202c.278.084.455.033.51 0");
}

.ng8osx0km {
  d: path("M13.533 11.738c.067.06.286.148.463.21v.01h-.56c-.223-.144-.485-.62-.59-.813l-.05-.085q-.02-.024-.06-.03a.2.2 0 0 0-.058 0c-.05 0-.223.03-.312.072v-.096a.8.8 0 0 1 .737.033c.013.021.354.636.43.7");
}

.nh45bwbrt {
  stop-color: var(--svg-color--403021, #403021);
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

.nwiyiqbom {
  stop-color: var(--svg-color--f5f4ef, #f5f4ef);
}

.nzaoip1jk {
  fill: var(--svg-color--591812, #591812);
  d: path("m12.365 11.621l-.438.337h.867z");
}

.o3kk6kbma {
  d: path("M9.355 14.19h.068c.21.008.35.084.362.109c.008.021.35.632.43.699c.067.059.286.147.454.21l.004.005h-.56c-.223-.14-.484-.615-.59-.813l-.05-.084c-.03-.03-.092-.034-.126-.03c-.042 0-.215.034-.303.076v-.097a.8.8 0 0 1 .307-.075z");
}

.o9bacs-rg {
  stop-color: var(--svg-color--331b03, #331b03);
}

.oho10q29i {
  stop-color: var(--svg-color--9a4818, #9a4818);
}

.ok6xrtbdj {
  d: path("M11.293 12.973h.286v2.244h-.286z");
}

.omcvfq02s {
  stop-color: var(--svg-color--3e2a19, #3e2a19);
}

.onhyjw0fx {
  stop-color: var(--svg-color--623209, #623209);
}

.ordpw7e7g {
  d: path("M10.754 17.228a3.25 3.25 0 0 1-.505-1.28v-.004c0-.088 0-.278-.497-.526l-.374.11c.21.1.631.32.66.395c.026.08.152.602.211.855a2.46 2.46 0 0 0-2.652-.855l.067.337l.025.013l.009-.026a3.2 3.2 0 0 1 1.107-.054c.442.067.779.4 1.12.736c.35.341.699.687 1.17.754a3 3 0 0 1-.34-.455");
}

.osa178cpr {
  stop-color: var(--svg-color--491f06, #491f06);
}

.p5fwkxbof {
  stop-color: var(--svg-color--211104, #211104);
}

.p5m98dapk {
  stop-color: var(--svg-color--fef3d7, #fef3d7);
}

.p6yqf0zgy {
  stop-color: var(--svg-color--632006, #632006);
}

.pfqihubhq {
  stop-color: var(--svg-color--cc9777, #cc9777);
}

.pijof0a3a {
  stop-color: var(--svg-color--f9e7cd, #f9e7cd);
}

.pm1mcymjg {
  d: path("M6.136 7.81c.198.22.42.696.299 1.306c.084-.181.294-.387.732-.295l1.124.223a18 18 0 0 1-.884-1.204a2.05 2.05 0 0 0-1.04.009a1 1 0 0 1-.231-.038");
}

.ptw8_fbxn {
  d: path("M11.696 6.897c.106-.084.22-.336.266-.45v11.236c-.295-.269-.918-.391-1.2-.429c.088.152.252.345.332.43c-.471-.068-.82-.413-1.17-.758c-.337-.333-.678-.665-1.12-.733a3.1 3.1 0 0 0-1.107.055l-.341 1.435c-.185-.547-.842-1.477-1.145-1.877l.13-2.425l-.076-.135c-.698-1.242-1.103-1.953-.863-3.351c.106-.968.047-1.053-.27-1.54L4.907 8a4.25 4.25 0 0 1-.64-1.684C5.17 7.42 5.97 7.85 6.366 7.85a2.04 2.04 0 0 1 1.066 0c.029-.03.332-.084 1.305-.076c.98.008 1.553-.147 1.717-.227c.37-.181 1.137-.56 1.242-.649m.53 0c-.109-.084-.222-.336-.264-.45v11.236c.29-.269.917-.391 1.2-.429a3 3 0 0 1-.333.43c.467-.068.82-.413 1.17-.758c.337-.333.674-.665 1.116-.733a3.1 3.1 0 0 1 1.111.055l.341 1.435c.186-.547.842-1.477 1.145-1.877l-.134-2.425l.076-.135c.703-1.242 1.102-1.953.867-3.351c-.105-.968-.05-1.053.27-1.54L19.016 8c.332-.509.55-1.083.64-1.684c-.905 1.103-1.705 1.533-2.1 1.533a2.04 2.04 0 0 0-1.065 0c-.03-.03-.333-.084-1.306-.076c-.98.008-1.557-.147-1.717-.227c-.37-.181-1.137-.56-1.242-.649");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q2e2p0mtm {
  stop-color: var(--svg-color--392c1c, #392c1c);
}

.q48t9607c {
  d: path("m13.162 10.88l.21-.013c.143.395.352.763.62 1.087c-.17-.068-.392-.156-.46-.21c-.075-.068-.416-.683-.429-.704c-.008-.021-.152-.097-.362-.11a.8.8 0 0 0-.375.076v-.151h.312c.252 0 .37-.21.37-.43c0-.219-.118-.463-.37-.463c-.089 0-.244.038-.312.055c.118-.122.274-.21.442-.194a.58.58 0 0 1 .527.484c.03.224-.106.476-.173.573");
}

.q6hyxobqu {
  fill: var(--svg-color--bca98a, #bca98a);
  d: path("M7.015 8.169c-.097.021-.169.126-.19.177c.152-.156.362-.084.45-.034c-.046-.055-.168-.156-.26-.139z");
}

.q95xftbio {
  stop-color: var(--svg-color--b96833, #b96833);
}

.qaujelb6y {
  fill: var(--svg-color--19150a, #19150a);
  d: path("M7.845 8.068c.472-.05.724-.03 1.006-.013c.21.013.43.03.77.021a5 5 0 0 0 1.537-.433l.101.164l.274-.164l.43.294v-.185l-.363-.27a.32.32 0 0 0-.265.051c0-.042-.025-.126-.13-.084l-.106.05c-.231.118-.74.371-1.326.422c-.294.029-.598.016-.892.004c-.409-.017-.796-.03-1.095.063l.06.084z");
}

.qblcy-blj {
  stop-color: var(--svg-color--eee6db, #eee6db);
}

.qcrmex6dh {
  fill: var(--svg-color--391101, #391101);
  d: path("M5.331 13.662c-.273.084-.45.033-.505 0c.126.185.265.273.362.303c.084.03.143-.025.22-.06c.113-.041.18-.041.222-.041c-.118-.215-.248-.228-.299-.202");
}

.qey2f0bsa {
  stop-color: var(--svg-color--05050c, #05050c);
}

.qhcwx2b4t {
  d: path("M9.05 12.973h.307v2.244H9.05z");
}

.qkve6ibea {
  stop-color: var(--svg-color--ffef94, #ffef94);
}

.qoc9pykas {
  fill: var(--svg-color--221913, #221913);
  d: path("M4.055 8.636c.042.219.143.614.265.74c.208.303.358.641.442.998v.043a2.8 2.8 0 0 0-.404-.581c-.113-.14-.21-.253-.236-.358a4.6 4.6 0 0 1-.067-.842");
}

.qoujutbnr {
  stop-color: var(--svg-color--f3e7cd, #f3e7cd);
}

.qsfehi76q {
  stop-color: var(--svg-color--fae7a2, #fae7a2);
}

.qz2h5i9zs {
  d: path("M16.228 16.252v-.013l.934-3.464c.838-1.348.729-2.383.387-3.427a1.58 1.58 0 0 1 .24-1.537c.434-.126 1.116-.573 1.87-1.495a3.6 3.6 0 0 1-.548.96a6 6 0 0 1-.379.434c-.345.379-.69.758-.732 1.204c-.03.307.025.627.084.977c.042.244.084.505.101.783c.055.783-.42 1.78-.673 2.176l-.632 1.348l-.316 3.464l-.337-1.414z");
}

.r6r6jgbjf {
  d: path("m6.21 15.33l.32.358c-.016-.16-.008-.522.131-.678h.518a.84.84 0 0 1 .164.678l.337-.358l-.168-.568h-.223l-.034.03H6.64l-.033-.03h-.22z");
}

.r8fz4wbpg {
  fill: var(--svg-color--221913, #221913);
  d: path("M19.944 8.636c-.042.219-.143.614-.265.745c-.208.3-.358.638-.442.993v.043c.118-.24.274-.426.404-.581c.114-.14.21-.253.236-.358q.072-.418.067-.842");
}

.rmy4mpbca {
  d: path("m15.667 8.624l.472-.632c-.514-.168-1.284 0-1.987-.067c-.708-.068-1.301-.421-1.432-.476c-.105-.042-.13.042-.13.084a.32.32 0 0 0-.265-.05l-.363.27v.386c.114 0 .186.08.211.118h2.58c.46 0 .8.244.914.367");
}

.s-gv73khp {
  d: path("M10.279 16.917c-1.027-1.069-1.937-.98-2.703-.98l1.196-.582l.682.16l.585.358c.042.026.067.148.076.194l.168.85z");
}

.s5npxkbyy {
  d: path("M7.697 16.252v-.013l-.935-3.464c-.838-1.348-.728-2.383-.387-3.427a1.58 1.58 0 0 0-.24-1.537c-.434-.126-1.116-.573-1.87-1.495c.14.375.337.687.548.96c.114.148.244.295.379.434c.345.379.69.758.732 1.204c.03.307-.025.627-.084.977a7 7 0 0 0-.1.783c-.056.783.42 1.78.669 2.176l.635 1.348l.316 3.464l.337-1.414z");
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

.sfal9o2cv {
  fill-rule: evenodd;
  d: path("M6.654 12.969h.732l.75 2.484l.155.236l-.606-.354l-.177-.573H7.29l-.033.03H6.64l-.034-.03H6.39l-.177.573l-.607.353l.156-.235l.889-2.484zm.076 1.608l-.043-.063l.253-.939h.084l.19.939l-.08.063z");
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

.swssssb7k {
  stop-color: var(--svg-color--8c653c, #8c653c);
}

.sxiw3wbga {
  stop-color: var(--svg-color--352c7d, #352c7d);
}

.t6l0aybgj {
  fill: var(--svg-color--bca98a, #bca98a);
  d: path("M16.91 8.169c.097.021.168.126.19.177c-.152-.156-.367-.084-.456-.034c.051-.055.169-.156.266-.139z");
}

.t7ysynb7s {
  stop-color: var(--svg-color--8f4a12, #8f4a12);
}

.tcjcxtbom {
  d: path("m8.333 9.045l-.901-1.196c.03-.03.332-.084 1.305-.076c.98.009 1.553-.147 1.717-.227q.635-.297 1.242-.648c.106-.084.22-.337.266-.45v2.05l-.013.092c-.008 0-.017.017-.021.034c-.009.02-.021.042-.042.042H9.124c-.43 0-.707.253-.791.379m-.548-1.053l.472.632c.245-.234.57-.365.91-.366h2.584a.24.24 0 0 1 .21-.118v-.388l-.361-.27a.32.32 0 0 0-.266.051c0-.042-.025-.126-.13-.084l-.106.05c-.231.119-.74.371-1.326.422c-.294.03-.597.017-.892.004c-.408-.017-.796-.03-1.095.063z");
}

.tinlozztt {
  d: path("m11.958 15.764l-.548.345c-.08-.063-.29-.151-.484-.02c-.008.012-.055.029-.151-.034l-.266-.16l-.778-.489l-.089.101l.59.38c.092.643.463 1.367.53 1.367c.282.038.91.16 1.2.43v-1.92z");
}

.tkeuenk-g {
  d: path("M11.958 15.764c.143.084.446.278.552.345c.084-.063.294-.151.484-.02c.012.012.059.029.155-.034q.522-.327 1.045-.649l.084.101l-.59.38c-.088.643-.463 1.367-.526 1.367c-.286.038-.91.16-1.2.43v-1.92z");
}

.tntj13thg {
  stop-color: var(--svg-color--aa6c33, #aa6c33);
}

.toe9lvbna {
  d: path("M10.737 10.686v-.649c.03-.008.021 0 .06 0h.045a.44.44 0 0 1 .282.097l.16-.45H9.98l.106.092v2.089l-.11.092h1.297l.19-.337h-.725v-.614h.046q.079 0 .152.03l.072.024l.227-.379h-.497zm.425.631h.295c.11 0 .21.06.265.152a.3.3 0 0 1 0 .295l-.185.29a.31.31 0 0 1-.27.156H9.972a.31.31 0 0 1-.286-.198c-.047-.118-.013-.202.084-.286h.004V9.945a.295.295 0 0 1-.088-.337a.31.31 0 0 1 .286-.198h1.305a.31.31 0 0 1 .253.126a.3.3 0 0 1 .042.278l-.156.421a.3.3 0 0 1-.122.152a.31.31 0 0 1 .252.299a.3.3 0 0 1-.042.151l-.235.38a.3.3 0 0 1-.106.104z");
}

.twneb2sbd {
  d: path("M7.706 9.714h.307v2.244h-.307z");
}

.txkv6dzmq {
  stop-color: var(--svg-color--0a0904, #0a0904);
}

.ty9x7ebll {
  stop-color: var(--svg-color--df8338, #df8338);
}

.tycvg-stn {
  d: path("M8.363 12.829a.31.31 0 0 1 .291-.198H9.74a.956.956 0 0 1 .935.951a.88.88 0 0 1-.261.636c.155.35.383.665.492.796l.005.004a.3.3 0 0 1 .042.32a.31.31 0 0 1-.278.177h-.56a.3.3 0 0 1-.169-.047a1 1 0 0 1-.202-.18a.31.31 0 0 1-.299.227h-.791a.31.31 0 0 1-.29-.198a.3.3 0 0 1 .071-.316v-1.819a.36.36 0 0 1-.072-.353m.291.139l.084.075v2.097l-.084.072h.791l-.088-.072v-.855h.046l.05.013l.026.021l.042.076v.004l.143.253c.127.21.295.463.45.56h.56a3.5 3.5 0 0 1-.614-1.065l-.013-.022v-.004a.63.63 0 0 0 .32-.539a.62.62 0 0 0-.627-.614zm.703.282v.863a.35.35 0 0 0 .307-.169a.55.55 0 0 0 0-.522a.34.34 0 0 0-.307-.168z");
}

.u-o8pjb3w {
  stop-color: var(--svg-color--d89d1d, #d89d1d);
}

.u2tijnjuy {
  stop-color: var(--svg-color--fbedd0, #fbedd0);
}

.u6lrxlzxu {
  fill: var(--svg-color--c4802f, #c4802f);
  d: path("M19.24 10.412c-.087-1.031.464-1.389.717-1.789c0 .396-.055.733-.08.855c-.06.223-.417.484-.636.934");
}

.ucxb3w3ji {
  d: path("M13.642 16.917c1.032-1.069 1.937-.98 2.707-.98l-1.2-.582l-.682.16l-.58.358c-.043.026-.072.148-.077.194z");
}

.udnqcob7n {
  d: path("M15.975 11.802c.362-.101.631-.665.463-1.196c-.177-.534-.792-.842-1.166-.732c-.421.122-.657.669-.485 1.204c.177.534.733.854 1.188.724m.156-1.107c.138.395.042.93-.169.997c-.143.042-.682-.206-.85-.682c-.127-.35-.076-.93.21-1.019c.202-.063.657.266.809.704");
}

.ufq5i8bws {
  d: path("M13.41 16.294c.038-.009.072 0 .046.071q-.12.335-.26.661c-.013.03-.043.097-.068.097h-.008c-.076 0-.573-.013-.952.202c-.05.034-.151.03-.088-.08a2 2 0 0 1 1.023-.219c.088-.202.248-.577.307-.732");
}

.ugjhvwb5d {
  fill: var(--svg-color--c4802f, #c4802f);
  d: path("M4.759 10.412c.088-1.035-.463-1.389-.716-1.789c0 .396.055.733.08.855c.059.223.417.484.636.934");
}

.ugsx3wbjm {
  stop-color: var(--svg-color--e4af47, #e4af47);
}

.ukdsjjb4d {
  d: path("M10.08 9.714h.286v2.244h-.286z");
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

.uuqza_bml {
  stop-color: var(--svg-color--914a2c, #914a2c);
}

.uz9r4gbrw {
  stop-color: var(--svg-color--f3efee, #f3efee);
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

.v2wp01uwu {
  d: path("m11.58 14.879l-.4.337h1.3l.186-.337h-1.09z");
}

.v8zcg6b8e {
  stop-color: var(--svg-color--662d15, #662d15);
}

.ve8bibb9a {
  fill-rule: evenodd;
  d: path("M16.822 12.82h.736l.75 2.48l.151.278l-.602-.396l-.177-.572h-.219l-.033.034h-.615l-.034-.034h-.218l-.177.572l-.607.396l.156-.278l.889-2.484zm.075 1.604l-.042-.062l.253-.94h.088l.185.94l-.075.063z");
}

.vfa93d36o {
  stop-color: var(--svg-color--d18a20, #d18a20);
}

.vi-dtpbsz {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M10.947 10.847h-.58v-.164h.867l-.283.164z");
}

.vky08jbfa {
  d: path("M6.62 8.8a3 3 0 0 0-.198-.736c.301-.102.625-.117.934-.043c.118.198.354.594.329.603c-.034.012-.594-.127-.737-.127c-.114 0-.27.198-.328.3z");
}

.vo0bpof5f {
  stop-color: var(--svg-color--412613, #412613);
}

.vpnwt3bic {
  stop-color: var(--svg-color--e2aa79, #e2aa79);
}

.vw08jibsn {
  stop-color: var(--svg-color--ffcb7a, #ffcb7a);
}

.vz_g-pbqr {
  d: path("M11.958 8.257V8.14c.118 0 .19.08.21.118h2.586c.458 0 .8.244.913.366l.421-.564c.042-.008.105 0 .076.068c-.042.097-.455.585-.484.606c-.013.008-.06-.025-.13-.067c-.14-.085-.363-.224-.565-.245c-.244-.03-1.79-.012-2.526 0h-.253c-.05 0-.1-.05-.143-.092c-.042-.038-.071-.072-.1-.072z");
}

.w_ns7fs-b {
  stop-color: var(--svg-color--f5f3e7, #f5f3e7);
}

.w0ex36jbj {
  d: path("M7.37 9.714h.336v2.244h-.337z");
}

.w2h3bbbfx {
  stop-color: var(--svg-color--c7a991, #c7a991);
}

.w6r_bnhhz {
  stop-color: var(--svg-color--a95817, #a95817);
}

.w76h2-b1i {
  fill-rule: evenodd;
  d: path("M15.755 11.962h.009a1.23 1.23 0 0 0 .59-.236a1.1 1.1 0 0 0 .437-1.031a1.192 1.192 0 0 0-1.558-.952a1.136 1.136 0 0 0-.8 1.234a1.183 1.183 0 0 0 1.322.985m.026-.295q.121.039.185.026l.02-.013a.3.3 0 0 0 .127-.143a1.23 1.23 0 0 0 .021-.842A1.18 1.18 0 0 0 15.47 10a.27.27 0 0 0-.151-.008a.3.3 0 0 0-.144.105l-.029.05c-.126.22-.126.602-.034.863c.127.35.446.581.67.657m-.367-1.376a.7.7 0 0 0-.059.281c0 .127.017.253.047.35a.8.8 0 0 0 .446.459v-.004a.96.96 0 0 0-.009-.59a.97.97 0 0 0-.425-.497m1.684.37c.101.775-.488 1.44-1.309 1.537l-.21.012c-.737-.012-1.352-.492-1.449-1.2a1.43 1.43 0 0 1 1.293-1.587a1.49 1.49 0 0 1 1.675 1.238");
}

.w8ys6zbol {
  d: path("m15.38 12.968l-.097.084l.009 2.16h-.636l-.859-1.213v1.12l.11.093h-.792l.148-.11v-2.004l-.169-.126h.56l.91 1.334l.059.085h.096v-1.34l-.13-.083zm-.968.252l-.025-.02a.36.36 0 0 1-.084-.371a.3.3 0 0 1 .286-.198h.791c.127 0 .245.08.29.198a.37.37 0 0 1-.08.362l.01 2.02c0 .08-.03.156-.09.211a.3.3 0 0 1-.218.093h-.636a.31.31 0 0 1-.252-.127l-.228-.324c.042.076.05.169.021.253a.31.31 0 0 1-.29.198h-.792a.308.308 0 0 1-.299-.38a.3.3 0 0 1 .097-.155l.026-.017v-1.726l-.043-.042c-.1-.08-.134-.248-.092-.366a.31.31 0 0 1 .29-.198h.56c.105 0 .198.05.253.135l.505.774zm-.27 1.798l-.037-.055v.017z");
}

.w9hsc3n3c {
  fill: var(--svg-color--4d0206, #4d0206);
  d: path("M6.527 15.687h-.922l.607-.354l.32.354zm.817 0l.337-.354l.61.354z");
}

.wig9qtbgj {
  stop-color: var(--svg-color--e0bfa0, #e0bfa0);
}

.wilor5buq {
  stop-color: var(--svg-color--130a03, #130a03);
}

.winlh2cjr {
  fill: var(--svg-color--331200, #331200);
  d: path("M4.868 13.326c-.219 0-.37-.315-.417-.463c.32.207.505.106.674.118c.126.008.265.248.316.366c-.35-.27-.295-.02-.573-.02");
}

.wm7rzrk8w {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m10.366 10.041l-.396-.357h1.305l-.24.223c-.299-.013-.299-.013-.67.134");
}

.womd-bbas {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M10.948 10.847h-.56v-.164h.846l-.282.164z");
}

.wzi8kgbcv {
  stop-color: var(--svg-color--ba8342, #ba8342);
}

.x1vbayu6s {
  stop-color: var(--svg-color--efc123, #efc123);
}

.x31ma4brj {
  d: path("M10.233 15.882c.252.16.505.295.673.345a.73.73 0 0 1 .472 0l.585-.278v-.185l-.547.345c-.085-.063-.295-.151-.489-.02c-.008.012-.054.029-.151-.034l-.265-.16l-.78-.489l-.07.085c.125.088.294.21.475.328l.1.063z");
}

.x9-wmpnpy {
  stop-color: var(--svg-color--ffe577, #ffe577);
}

.x97dedk8b {
  d: path("M10.245 16.779c.03.113-.017-.085 0 0a2.45 2.45 0 0 0-2.648-.855v.012h.143c.732-.008 1.583-.012 2.538.981z");
}

.x99edrb4i {
  d: path("M8.94 9.714h.329v2.244H8.94z");
}

.xi2vqyolr {
  fill: var(--svg-color--2d0700, #2d0700);
  d: path("M4.642 12.034a1 1 0 0 0-.53-.455c.1.097.054.303.244.745c.155.37.505.278.635.181c-.05-.038-.193-.19-.35-.471");
}

.xp4q1n14p {
  fill: var(--svg-color--fff8f2, #fff8f2);
  d: path("M7.706 10.661H8.94v.173H7.706z");
}

.xr1bi6b-r {
  stop-color: var(--svg-color--010508, #010508);
}

.xrjg-tb9l {
  d: path("M17.558 12.518a.3.3 0 0 1 .295.214l.737 2.442l.13.202a.3.3 0 0 1-.105.422a.3.3 0 0 1-.156.041h-.943a.31.31 0 0 1-.298-.217a.3.3 0 0 1-.01-.128a.66.66 0 0 0-.029-.337h-.151l-.013.076a1.6 1.6 0 0 0-.009.278a.3.3 0 0 1-.08.232a.3.3 0 0 1-.227.096h-.922a.306.306 0 0 1-.308-.31a.3.3 0 0 1 .047-.153l.135-.21l.884-2.446a.3.3 0 0 1 .286-.202zm-1.71 3.018l.085-.236l.888-2.483h.737l.75 2.483l.151.278h-.943a1.4 1.4 0 0 0 0-.345a.73.73 0 0 0-.168-.379h-.514c-.084.097-.122.261-.135.413c-.008.105-.03.206-.025.27zm1.011-1.179l.05.068h.396l.072-.085l-.181-.917h-.084l-.253.93z");
}

.xtpkynb9n {
  stop-color: var(--svg-color--d9d9d9, #d9d9d9);
  stop-opacity: 0;
}

.xyjh2fa4b {
  d: path("M8.742 12.973h.308v2.244h-.308z");
}

.xz1_ucioz {
  d: path("m16.379 15.183l.32.396c-.013-.16-.009-.565.135-.72h.518c.075.08.214.366.164.72l.337-.396l-.173-.573h-.219l-.034.034h-.614l-.034-.034h-.219l-.177.573z");
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

.ydq49s4wy {
  d: path("M13.17 17.228c.14-.18.396-.657.506-1.28v-.004c0-.088 0-.278.497-.526l.374.11c-.21.1-.631.32-.66.395c-.026.08-.152.602-.211.855a2.455 2.455 0 0 1 2.652-.855l-.067.337l-.026.013l-.008-.026a3.1 3.1 0 0 0-1.111-.054c-.438.067-.775.4-1.116.736c-.35.341-.703.687-1.17.754a3 3 0 0 0 .34-.455");
}

.yf-3s96du {
  stop-color: var(--svg-color--683b24, #683b24);
}

.ygja7ia_w {
  stop-color: var(--svg-color--090c03, #090c03);
}

.ynsb2_ycx {
  d: path("M19.872 11.596a2 2 0 0 0-.391.631c-.105.249-.29.308-.463.287l-.009-.009c.05-.038.194-.19.35-.471c.16-.286.42-.421.53-.455l-.012.017z");
}

.za1aw8bfm {
  stop-color: var(--svg-color--36271c, #36271c);
}

.zcbo6vbdf {
  stop-color: var(--svg-color--6f4d28, #6f4d28);
}

.zngk21bek {
  fill: var(--svg-color--f8f2de, #f8f2de);
  d: path("m11.58 13.306l-.4-.337h1.309l-.24.198c-.286-.042-.455-.013-.674.139z");
}

</style>
