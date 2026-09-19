<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="oru17m-cm"/><path class="v-49kgb1k"/><g class="d2kvgvbvc"><path class="yudtzbciv"/><path class="b4_w4094x"/><path class="weeb7rb5y"/><path class="xv7-sebxa"/><path class="owl2b-b7t"/><path class="cv9ezkc9t"/><path class="s956sqbem"/><path class="h2m5sbb5s"/><path class="ja3p_ebog"/><path class="q89y039tv"/><path class="c7kcr6-dc"/><path class="ytg0e6bga"/><path class="e9wkmcmom"/><path class="o5b_jobcj"/><path class="u5aon3lel"/><path class="nbgi7dbzk"/><path class="f3b8l45lk"/><path class="cqk69cc3d"/><path class="cy-ms4bfk"/><path class="w8vnhsfuc"/><path class="jmseg9beu"/><path class="qn8rdtwqv"/><path class="ky11mebgv"/><path class="d2yygp2em"/><path class="x1p7g9mtu"/><path class="ka0v6iaai"/><path class="k5u-47bvk"/><path class="gxy88xv-i"/><path class="gcjb-r0qq"/><path class="oe-g602cf"/><path class="jjngsubpu"/><path class="nq1gyhyrz"/><path class="g0srzz9xf"/><path class="nmek-raev"/><path class="gieuhuoas"/><path class="nsr25my4l"/><path class="za_-5y_wc"/><path class="elkmyob3g"/><path class="r2sns8-zn"/><path class="aec3sgbzb"/><path class="qo_dr2bwt"/><path class="wl-mlkhur"/><path class="mmkkn4bwk"/><path class="obp4udb3r"/><path class="y1z9oabpi"/><path class="px-zfqs0j"/><path class="rn978y6zc"/><path class="v99pg2aml"/><path class="cz31oev6l"/><path class="oxjqouzya"/><path class="br-n2ebcn"/><path class="gfx40ubjf"/><path class="xj-euxbko"/><path class="nfyzklbzc"/><path class="lv2xqbbmk"/><path class="bdgyzk1ab"/><path class="qjpv6wirl"/><path class="y-w_9vbhv"/><path class="m5soovbiw"/><path class="fiwxokb8f"/><path class="ng_20ybpy"/><path class="qpp0m4luj"/><path class="gb6fb_b0g"/><path class="b_verq-ww"/><path class="hpyi2mblk"/><path class="sm6gf44xn"/><path class="j_8nulbcl"/><path class="z5don_s7u"/><path class="djxeqibne"/><path class="mhszp0qvm"/><path class="xa96a2xlo"/><path class="z5d3xv9dg"/><path class="qy-ci4bix"/><path class="kb68azpux"/><path class="d9h5bdbfi"/><path class="cwr6nsbym"/><path class="l1dhfqb1h"/><path class="fh21t3rme"/><path class="zm8r0kqej"/><path class="v3wt20fyk"/><path class="hinsp-rcu"/><path class="fcuubqchk"/><path class="ukuy2ybem"/><path class="w0q5m4xst"/><path class="nyh2v3srn"/><path class="ji6r_8bek"/><path class="sxzp-s3wb"/><path class="ha9z0znhd"/><path class="x3699jbel"/><path class="e30f18bel"/><path class="njmkf9_jl"/><path class="see_nbbkr"/><path class="el7m9r2js"/><path class="gdpozpaiv"/><path class="uci9k5-1o"/><path class="bgxj8kb_q"/><path class="xqml7b_ww"/><path class="auj9rccup"/><path class="z_tv3gb5e"/><path class="c--rmch-t"/><path class="vg5f9fbqi"/><path class="ybo2ns_xg"/><path class="p0p59nrae"/><path class="gh10sebnn"/><path class="wenhe9bpv"/><path class="vm7eq4bqb"/><path class="hqx0rfqkk"/><path class="eca_ijb2e"/><path class="yignl5buv"/><path class="cwslaxboi"/><path class="q8-96abvf"/><path class="gebjc_-ic"/><path class="l6bxbobfn"/><path class="s71alqb9h"/><path class="o8nw70b8y"/><path class="o0srk9bqs"/><path class="yx3b6lbgi"/><path class="jcw_j7bvd"/><path class="u6y11hr8k"/><path class="yw4x6vbgs"/><path class="q0qbyk_jx"/><path class="mur8xxm0p"/><path class="v3ftc1b1v"/><path class="lo66k7tqp"/><path class="bk49pebbd"/><path class="iuqjxz_8s"/><path class="i394qvbdy"/><path class="v7q-qmoin"/><path class="cj19icdnr"/><path class="mqxh9abgx"/><path class="qnf0dhdwk"/><path class="k_rjucckx"/><path class="bv7tpmb2g"/><path class="w3mew4b-l"/><path class="w-w45ubqe"/><path class="bh7o_vbhy"/><path class="p2d72acqh"/><path class="s100d1fby"/><path class="t1ubx3lef"/><path class="zwz361bjz"/><path class="wumkggtxl"/><path class="pnb4dn_6r"/><path class="pmfpf1b3k"/><path class="otiktj-hg"/><path class="j61z68bjo"/><path class="iywnp160a"/><path class="x57a214ao"/><path class="ozvfyib9v"/><path class="ogsln1ckz"/><path class="xf_wiachn"/><path class="zuwefd0yd"/><path class="nq-p6ru4p"/><path class="li8xymbwo"/><path class="ku3ml56su"/><path class="oegl06bwv"/><path class="m4tc0_7xf"/><path class="sr7ufkbjw"/><path class="ilspkrb5a"/><path class="z06g8hrrz"/><path class="xy70yxbvt"/><path class="q1juixquy"/><path class="ed_-tmlos"/><path class="svzfct59i"/><path class="hdm0a6b4n"/><path class="ijolx--_j"/><path class="bz3bpacbz"/><path class="g16-trnth"/><path class="qrx1kzxgi"/><path class="p_r0gc4zq"/><path class="gbx-o-j5r"/><path class="baq6zjb_n"/><path class="a1ckq2wqg"/><path class="g-izvun6l"/><path class="zk16wvbrd"/><path class="tk3mlm3hc"/><path class="tj_wsv6uj"/><path class="qk5cvhrht"/><path class="x567okbom"/><path class="mxxko4xkl"/><path class="km3m8rvwg"/><path class="y32ampb5k"/><path class="s13f27-xx"/><path class="mk4o1acut"/><path class="yi2wtcceh"/><path class="x9u-gcbqb"/><path class="ta525sf7k"/><path class="ux5h8gbnw"/><path class="p51vv7b3x"/><path class="sfqh83bbe"/><path class="c5u0f7b3h"/><path class="luq9xmbim"/><path class="a32s9db7w"/><path class="zovbtd9xr"/><path class="grh7cvuoo"/><path class="qq4baabpl"/><path class="sqiy7ebay"/><path class="leg6h1bwm"/><path class="e04ow70ee"/><path class="s3gjzdqok"/><path class="aqy29m8iz"/><path class="xd4-_3q0x"/><path class="eexyhhb5k"/><path class="n8z1vkbtg"/><path class="bnp4e_19g"/><path class="nd_4asmbx"/><path class="auidx6b_j"/><path class="vs-2aacwz"/><path class="ib-rtub4k"/><path class="xc6cifb4y"/><path class="swl7yd87j"/><path class="bxcatnb6u"/><path class="yi3qbga1c"/><path class="c4bh7hhys"/><path class="u0eevxm5o"/><path class="spfudib2s"/><path class="g5fh_pdnj"/><path class="s4nq-ub6a"/><path class="fxar9gb1u"/><path class="yc0dyqzpl"/><path class="z-6xz4khx"/><path class="xqvvy442h"/><path class="yr49opzwo"/><path class="dvray4bge"/><path class="cm3hh8bmx"/><path class="eeiu44nui"/><path class="e17mbkb8l"/><path class="sbg-f8bxq"/><path class="l4eor6b4o"/><path class="yfo-mpbcv"/><path class="fnhxdh6ab"/><path class="i8led9bqb"/><path class="rrr7qsbpw"/><path class="yz8lgob8x"/><path class="x2wwb4_xx"/><path class="xm3s8hb-x"/><path class="vq4blbgoo"/><path class="de_yc9ccd"/><path class="p1--7zv7p"/><path class="p0xhbe13u"/><path class="yw82gtb5e"/><path class="uvhf2ub6f"/><path class="qvr4wjb2y"/><path class="vc18zkcna"/><path class="gnktfvbdn"/><path class="c78p8hsda"/><path class="nrdq6-1xk"/><path class="tzc3kkb_o"/><path class="rypo7sgde"/><path class="vw89uc0cj"/><path class="gk51zhtkt"/><path class="li-80dbaf"/><path class="zj9qhsbvg"/><path class="jbjhttbuv"/><path class="aac2ztcbf"/><path class="tyh2njbrh"/><path class="hgg2gdbpl"/><path class="os78g6bel"/><path class="rwgrv-bzg"/><path class="qangk_bnj"/><path class="suwnyq7ix"/><path class="o7q9w4ejw"/><path class="dyg04fboi"/><path class="w7a-bublj"/><path class="lo-b_wbhh"/><path class="frb_zyb2n"/><path class="ai8l3tl3f"/><path class="v85b83bxw"/><path class="i_ok185dp"/><path class="cbp4iybai"/><path class="aqydl-6aq"/><path class="o4itg_wcw"/><path class="oq6hhfrdl"/><path class="wc7pcdbvw"/><path class="t-vo-nbbq"/><path class="wazusbbjv"/><path class="mx3abbcne"/><path class="j_kgbac6y"/><path class="h7uqzybof"/><path class="dv2azdb6r"/><path class="wumaxgi2p"/><path class="rj7vbxb3e"/><path class="d9_4857tq"/><path class="yl4m4-7ep"/><path class="p5z2ihb8l"/><path class="b-cwnq-zk"/><path class="r0y-r3tny"/><path class="r9d8c4-6s"/><path class="e6iiv2y4y"/><path class="jez-8_bet"/><path class="h6dztrbgr"/><path class="bxfl5lbbe"/><path class="ihkg6mw0l"/><path class="t_ua8_60e"/><path class="dt6s14bdc"/><path class="cmsg10byx"/><path class="mldi_7bhz"/><path class="r26ca2bal"/><path class="tdgna6buo"/><path class="jtkewxbbv"/><path class="d7q_kkjfu"/><path class="urb9mhcnw"/><path class="azd89nbfd"/><path class="tqiy4qbfs"/><path class="ssmsarbcn"/><path class="ikx50uv5h"/><path class="xl4aeibwy"/><path class="qkvdppdih"/><path class="skjo1pble"/><path class="pbrh9obtg"/><path class="y-nrx8t0b"/><path class="rblh9ibhc"/><path class="ua9oanbqj"/><path class="si_hjebbs"/><path class="chvvipbla"/><path class="x4clsw5cj"/><path class="fvr583b1t"/><path class="tqipfrbha"/><path class="gvbii6bnn"/><path class="nt6g6_nyk"/><path class="r1ihm6buz"/><path class="tci3nzbmp"/><path class="rd8e6ecpz"/><path class="vlgrpbysy"/><path class="ltdjgxbin"/><path class="dzcpnybhi"/><path class="bx83hab_i"/><path class="l_37ylb8a"/><path class="cclfpgczg"/><path class="t698ne93g"/><path class="b599k61-v"/><path class="bftzr07nt"/><path class="ki0hl23ip"/><path class="qbanncbgl"/><path class="dmks28fkd"/><path class="knblg2bpz"/><path class="usou6ib7g"/><path class="ibfgn0bgu"/><path class="ymkoa6brj"/><path class="b36je-bbh"/><path class="kttybh77k"/><path class="kklw3kbqg"/><path class="n3wpa6bkt"/><path class="c_640efyf"/><path class="ejqm_d-zr"/><path class="sn56qrs6s"/><path class="kllft4a3g"/><path class="xvfqkxfun"/><path class="szff83bpz"/><path class="ngf0nj-fj"/><path class="i9d0wdbxj"/><path class="xyn_s5b4s"/><path class="m7576zbiv"/><path class="z4ey4jb6v"/><path class="ocl8yrlzw"/><path class="ujs2_ub1y"/><path class="mzclkiawr"/><path class="erihlp3su"/><path class="tj897wbez"/><path class="se_dt1b3i"/><path class="wolu6dbdj"/><path class="zsm_40bkf"/><path class="rq_fhk1eq"/><path class="czbc4qlbx"/><path class="xkqez-bri"/><path class="gn0gwcb5s"/><path class="o_etcxbsu"/><path class="l3jgx7bbh"/><path class="d0x3u841o"/><path class="ram6q8bpg"/><path class="j7buelznk"/><path class="vv17s-ble"/><path class="nzm4a4bkr"/><path class="uhy9wx5zp"/><path class="s78pxubju"/><path class="x-lytkb-f"/><path class="wepy6vz-b"/><path class="z077yybii"/><path class="xmlg_vbri"/><path class="okj2pv4om"/><path class="hfpii4cxd"/><path class="q75m7cbet"/><path class="tjojx0bvt"/><path class="xuhvcjbpb"/><path class="ndlje-bbc"/><path class="o_d0-wb3a"/><path class="y7ici8ben"/><path class="n2oqopkls"/><path class="cz2mznbbe"/><path class="jkf2h3baj"/><path class="bwj624b8f"/><path class="n_nj63gtl"/><path class="ia_045zit"/><path class="is63r5b1b"/><path class="gkjqhtb3b"/><path class="t00h-1r_v"/><path class="oyhsv6qpe"/><path class="n_evikbtl"/><path class="gf5eeib5k"/><path class="czfdybjce"/><path class="eb5wkxbij"/><path class="n8vwtlfdz"/><path class="in28rk_ri"/><path class="gibdx_mcn"/><path class="v6tbxjplv"/><path class="tf0n1cclr"/><path class="d2l8_dbxg"/><path class="vdr_oabau"/><path class="q8tzxzbnb"/><path class="vbwld6bhk"/><path class="toode_bbt"/><path class="tfmqpt0ta"/><path class="jo-wtlf8h"/><path class="rj9d7be3k"/><path class="ufi795cxs"/><path class="kdesd-hay"/><path class="buf5ovbre"/><path class="lnw_t5b-m"/><path class="t8olxk_5t"/><path class="ki6w7kben"/><path class="j_0yt57tg"/><path class="zz5f71b5i"/><path class="qmkftpk4n"/><path class="sbh57nb2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-nicaragua" /></template>
<style>
.a1ckq2wqg {
  fill: var(--svg-color--796f42, #796f42);
  d: path("M26.513 28.681q-.033.033-.065.069c-.051-.048-.146-.057-.145-.161c.103-.043.16.015.21.092");
}

.a32s9db7w {
  fill: var(--svg-color--c19f00, #c19f00);
  d: path("M25.768 32.21c.18.023.081.159.1.248c-.05.038-.061-.024-.091-.034c-.009-.02-.012-.039-.021-.059c-.005-.037.002-.073.004-.112z");
}

.aac2ztcbf {
  fill: var(--svg-color--71652d, #71652d);
  d: path("M28.382 38.08q.05-.059.099-.12c.024.062.05.12.079.193c-.082.004-.134-.019-.178-.073");
}

.aec3sgbzb {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M28.694 37.544c.008-.118.104-.18.169-.263c.113-.086.193-.027.266.063l.002.029a.18.18 0 0 1 .031.169q-.113.207-.338.151c-.066-.031-.14-.051-.13-.149");
}

.ai8l3tl3f {
  fill: var(--svg-color--8b7f49, #8b7f49);
  d: path("M34.68 25.424c.074.066.062.151.053.235c-.068-.067-.075-.149-.053-.235");
}

.aqy29m8iz {
  fill: var(--svg-color--7f7b67, #7f7b67);
  d: path("m29.439 25.26l-.036.004c-.002-.087-.013-.173-.005-.258c.01-.075.055-.075.101-.021c-.064.041-.048.104-.046.163z");
}

.aqydl-6aq {
  fill: var(--svg-color--887f52, #887f52);
  d: path("m37.937 28.362l.214-.019c-.063.123-.138.075-.214.019");
}

.auidx6b_j {
  fill: var(--svg-color--645d39, #645d39);
  d: path("M37.411 35.1c-.017.077.065.089.096.137c-.063.015-.128.027-.2.045c-.011-.089.032-.146.104-.182");
}

.auj9rccup {
  fill: var(--svg-color--766b3d, #766b3d);
  d: path("M36.23 26.05c.018-.039.033-.08.053-.121c.085.096.241-.046.33.104c-.134.065-.262-.009-.383.017");
}

.azd89nbfd {
  fill: var(--svg-color--7e7239, #7e7239);
  d: path("M37.621 35.834c-.102.005-.205.016-.292-.056c.099-.003.207-.031.292.056");
}

.b_verq-ww {
  fill: var(--svg-color--f1f1f1, #f1f1f1);
  d: path("M37.19 27.03c-.002.125-.089.214-.135.32c-.084-.095-.265-.136-.177-.324l.048.001c.088-.059.177-.07.264.003");
}

.b-cwnq-zk {
  fill: var(--svg-color--584e20, #584e20);
  d: path("m27.678 36.31l.055-.094c.074.016.144.067.104.132c-.034.057-.101-.047-.159-.038");
}

.b36je-bbh {
  fill: var(--svg-color--f4f4f3, #f4f4f3);
  d: path("m37.772 28.1l-.011-.118l.227-.163c.126-.008.159.087.198.178q.006.045.016.089c-.112.082-.196.218-.367.16c.009-.061-.029-.102-.063-.146");
}

.b4_w4094x {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("M31.854 24.568h.049a.8.8 0 0 1 .157.285c.027.11.027.224.003.334c-.025.097-.066.186-.16.236h.002c-.125.084-.263.053-.398.043c-.101-.048-.115-.133-.105-.23c.005-.188.01-.376-.01-.564a.15.15 0 0 1 .031-.084c.139-.107.283-.095.431-.02");
}

.b599k61-v {
  fill: var(--svg-color--fe5500, #fe5500);
  d: path("M33.446 29.26c-.379-.031-.757-.07-1.134-.092c-.531-.031-1.057.031-1.582.092a.7.7 0 0 1 .152-.32c.051.074.126.065.196.055c.739-.103 1.479-.076 2.22.003z");
}

.baq6zjb_n {
  fill: var(--svg-color--706329, #706329);
  d: path("M37.13 36.06q.035-.032.067-.065c.104.011.119.076.097.161l-.064.061z");
}

.bdgyzk1ab {
  fill: var(--svg-color--6b612f, #6b612f);
  d: path("M31.425 24.652c-.003-.219-.161-.112-.261-.12c.193-.12.588-.101.689.036c-.142.035-.311-.075-.428.084");
}

.bftzr07nt {
  fill: var(--svg-color--029e9e, #029e9e);
  d: path("M30.62 29.473c.222.052.437-.033.655-.046c.744-.05 1.486-.016 2.228.061c.143.021.198.13.246.244c-.41-.024-.812-.131-1.227-.147a10.3 10.3 0 0 0-2.1.149a.55.55 0 0 1 .198-.261");
}

.bgxj8kb_q {
  fill: var(--svg-color--68603b, #68603b);
  d: path("M29.439 25.26q.004.374.003.751q-.026.019-.05-.002l.011-.745q.015-.041.036-.004");
}

.bh7o_vbhy {
  fill: var(--svg-color--9d861b, #9d861b);
  d: path("M33.971 38.22c.015.044.075.087.002.131h-.132c-.048-.005-.092-.011-.119-.054a.46.46 0 0 1 .249-.077");
}

.bk49pebbd {
  fill: var(--svg-color--7c6f33, #7c6f33);
  d: path("M37.515 36.21a1 1 0 0 1-.067-.063c-.025-.066-.064-.127-.045-.206c.1-.01.192-.017.228.108z");
}

.bnp4e_19g {
  fill: var(--svg-color--776a2f, #776a2f);
  d: path("M38.52 35.03c.015.061-.019.144.074.174c-.012.041-.014.093-.072.093c-.046-.002-.053-.041-.051-.076q.006-.094.014-.186a.1.1 0 0 1 .035-.005");
}

.br-n2ebcn {
  fill: var(--svg-color--f8cc00, #f8cc00);
  d: path("M25.19 29.474c.004-.056.043-.084.094-.104c.091-.025.182-.054.269.017l.116.127c.032.08-.025.097-.082.116a.9.9 0 0 1-.33-.056q-.065-.03-.067-.1");
}

.buf5ovbre {
  fill: var(--svg-color--8ae674, #8ae674);
  d: path("M33.685 30.344q.046.02.095.037l-.169.071c-.028-.086.068-.062.074-.108");
}

.bv7tpmb2g {
  fill: var(--svg-color--665c2d, #665c2d);
  d: path("M32.92 25.477c.046-.049.091-.097.146-.153c.067.112.046.199-.053.269a.34.34 0 0 1-.093-.112z");
}

.bwj624b8f {
  fill: var(--svg-color--16cbfe, #16cbfe);
  d: path("M32.12 34.33v-.041h.326c-.139.07-.233.046-.326.041");
}

.bx83hab_i {
  fill: var(--svg-color--0152d6, #0152d6);
  d: path("M33.884 30a7.5 7.5 0 0 0-3.392-.057c-.061.014-.123.012-.186.018q.06-.112.116-.228c.314-.177.667-.2 1.01-.216c.578-.024 1.154-.041 1.731.048c.203.03.403.06.586.166c.047.091.122.165.136.269");
}

.bxcatnb6u {
  fill: var(--svg-color--665f3e, #665f3e);
  d: path("m30.02 25.744l.184.06c-.063.052-.13.1-.22.08q.017-.072.036-.14");
}

.bxfl5lbbe {
  fill: var(--svg-color--867422, #867422);
  d: path("M28.906 38.36c-.146-.017-.094-.139-.112-.219l.015-.007c.127.024.103.125.105.212z");
}

.bz3bpacbz {
  fill: var(--svg-color--72631f, #72631f);
  d: path("M25.693 28.3c.021-.086.064-.15.155-.246c.006.128.014.205-.072.26q-.045.025-.083-.014");
}

.c_640efyf {
  fill: var(--svg-color--f5f4f4, #f5f4f4);
  d: path("M38.725 32.683c.009-.07.025-.131.121-.097c.002.084.262.035.106.202c-.052.021-.091.075-.156.058c-.069-.035-.096-.089-.071-.163");
}

.c--rmch-t {
  fill: var(--svg-color--746939, #746939);
  d: path("M24.855 30.811c-.056.194.11.211.216.276c-.116-.03-.199.043-.354.152c.095-.185.047-.32.138-.428");
}

.c4bh7hhys {
  fill: var(--svg-color--6e653b, #6e653b);
  d: path("M37.2 28.25c.064.031.1-.052.16-.043q-.015.096-.025.199c-.091-.023-.108-.092-.135-.156");
}

.c5u0f7b3h {
  fill: var(--svg-color--84783e, #84783e);
  d: path("m28.23 36.631l-.071.069l-.092-.002c.015-.058.051-.119-.018-.171c.1-.033.132.054.181.104");
}

.c78p8hsda {
  fill: var(--svg-color--6e6746, #6e6746);
  d: path("m35.758 26.29l-.009.342c-.077-.116-.099-.232.009-.342");
}

.c7kcr6-dc {
  fill: var(--svg-color--eec503, #eec503);
  d: path("m36.945 27.83l-.033-.048c-.017-.046-.025-.089 0-.133c.002-.099.139-.166.07-.283a.12.12 0 0 1 .018-.068c.06-.092.101-.19.145-.291a.23.23 0 0 1 .071-.084c.069-.059.136-.119.233-.063a6 6 0 0 1-.366.86c-.048.031-.012.175-.138.11");
}

.cbp4iybai {
  fill: var(--svg-color--82701b, #82701b);
  d: path("m38.843 30.875l-.054.054l-.225-.007c.082-.075.184-.045.279-.047");
}

.cclfpgczg {
  fill: var(--svg-color--c054d6, #c054d6);
  d: path("M30.18 30.18c.27.059.518-.07.772-.118c.972-.181 1.924-.087 2.875.125c.06.013.117.052.176-.002l.142.27q-.18-.035-.362-.075c-.03-.015-.068-.014-.095-.037c-.494-.148-1-.194-1.511-.208c-.02.017-.039.014-.057 0a6.2 6.2 0 0 0-1.799.248q-.14.038-.283.068z");
}

.chvvipbla {
  fill: var(--svg-color--5a512a, #5a512a);
  d: path("M26.23 28.49q-.003.007-.009.015l-.024-.018q.009-.006.019-.016q.007.012.014.019");
}

.cj19icdnr {
  fill: var(--svg-color--796e39, #796e39);
  d: path("M27.374 37.31c.085.075.148.018.217-.033c-.043.072.058.122.025.213c-.114-.017-.196-.068-.242-.18");
}

.cm3hh8bmx {
  fill: var(--svg-color--7a724c, #7a724c);
  d: path("M31.384 38.713c.052.056.041.125.038.192c-.041-.133-.176-.128-.27-.182c.074-.049.155-.035.232-.01");
}

.cmsg10byx {
  fill: var(--svg-color--796a27, #796a27);
  d: path("M25.441 33.636q-.004.146-.003.292c-.088-.097-.084-.196.003-.292");
}

.cqk69cc3d {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("M34.11 37.918c.084.103-.085.117-.065.197c-.002.055-.007.105-.053.145c-.086.04-.181.04-.269.076c-.094.005-.153-.052-.198-.125c-.064-.106-.041-.206.027-.304c.07-.066.173-.021.25-.066a.16.16 0 0 1 .105-.013a.3.3 0 0 1 .092.041c.034.02.067.051.111.049");
}

.cv9ezkc9t {
  fill: var(--svg-color--f0c601, #f0c601);
  d: path("M26.668 26.896c.039-.025.074-.054.113-.082c.064-.032.078.018.095.062c.223.172.34.476.665.531c.07.011.05.106.007.153c-.06.065-.133.087-.206.018a42 42 0 0 1-.564-.545c-.022-.058-.165-.017-.11-.137");
}

.cwr6nsbym {
  fill: var(--svg-color--74682e, #74682e);
  d: path("M39.21 30.596c.059-.142-.069-.27-.036-.429c.225.154.141.366.147.554c-.084 0-.095-.065-.111-.125");
}

.cwslaxboi {
  fill: var(--svg-color--6b6135, #6b6135);
  d: path("M36.06 36.684c-.071.079-.03.159.04.255c-.111.001-.157-.037-.2-.085c-.011-.05-.064-.068-.078-.117c.066-.064.156-.069.238-.084z");
}

.cy-ms4bfk {
  fill: var(--svg-color--f7cc00, #f7cc00);
  d: path("M25.908 30.18c-.219-.013-.422-.085-.629-.147c-.058-.099-.219.015-.256-.125c-.009-.039-.017-.075.021-.104c.059-.051.123-.026.188-.018c.075.015.149.039.226.056c.114.026.225.059.306.156c.103.004.21.002.31.015c.081.012.04.055.014.089c-.038.075-.086.13-.18.078");
}

.cz2mznbbe {
  fill: var(--svg-color--1cbdfe, #1cbdfe);
  d: path("M29.586 34.2c-.103.054-.144-.028-.262-.026c.134-.077.184-.013.262.026");
}

.cz31oev6l {
  fill: var(--svg-color--73672e, #73672e);
  d: path("M26.718 34.99c-.15-.056-.182.094-.263.156c-.084-.106-.185.029-.271-.021c-.059-.037-.155-.031-.152-.137c.228-.014.456-.147.686.002");
}

.czbc4qlbx {
  fill: var(--svg-color--1dbafe, #1dbafe);
  d: path("M31.74 33.971c-.181-.043-.342-.202-.549-.089c.207-.116.396-.105.556.08z");
}

.czfdybjce {
  fill: var(--svg-color--f7ba01, #f7ba01);
  d: path("M30.557 32.471c.142.382.539.427.813.635c-.434-.112-.883-.189-1.092-.676c-.071-.171-.155-.335-.235-.501c.118-.115.2-.053.265.06c.053.089.097.183.145.272c.093.041.095.128.104.21m1.877.163c.174.233.441.315.691.429q.032.075-.046.056c-.693-.125-1.178-.636-1.161-1.22c.099-.045.131.056.193.086c.047.018.023.069.045.098c.029.123.091.227.161.331c.085.047.099.136.117.22");
}

.d0x3u841o {
  fill: var(--svg-color--21b2fe, #21b2fe);
  d: path("M33.845 34.22c-.112.023-.228.05-.339.076c.104-.061.188-.184.339-.076m-.545-.2c-.02.128-.111.192-.277.295a.9.9 0 0 1 .27-.301z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d2l8_dbxg {
  fill: var(--svg-color--4df0b1, #4df0b1);
  d: path("m33.29 31.14l.006.046c-.146.005-.297.043-.435-.041q-.026-.016-.021-.032q.011-.02.012-.019c.152.003.303-.046.438.046");
}

.d2yygp2em {
  fill: var(--svg-color--f2c702, #f2c702);
  d: path("M26.02 35.607q.055-.046.113-.087c.047-.082.047-.184.115-.256c.058-.064.128-.112.181-.181c.075-.089.15-.181.285-.094c.024.11-.075.154-.126.219c-.161.212-.335.415-.501.623c-.077.096-.087-.006-.118-.039c-.052-.081.012-.129.051-.185");
}

.d7q_kkjfu {
  fill: var(--svg-color--8b7f4b, #8b7f4b);
  d: path("M34.754 25.797c.118.034.085.133.085.217c-.088-.05-.043-.15-.085-.217");
}

.d9_4857tq {
  fill: var(--svg-color--988011, #988011);
  d: path("M32.494 25.475c-.092-.08-.063-.169-.008-.258c.039.028.031.065.012.103q0 .077-.004.155");
}

.d9h5bdbfi {
  fill: var(--svg-color--ecc201, #ecc201);
  d: path("M26.24 27.431c.259-.133.422-.07.437.171c-.054.055-.104.017-.155-.003q-.031-.018-.059-.038c-.055-.045-.126-.045-.188-.072a.07.07 0 0 1-.035-.058");
}

.de_yc9ccd {
  fill: var(--svg-color--736f5a, #736f5a);
  d: path("m26.668 36.432l.061.048c-.047.041-.104.086-.155.033c-.037-.038-.015-.097.035-.128z");
}

.djxeqibne {
  fill: var(--svg-color--706328, #706328);
  d: path("M32.498 25.05c.004-.146-.05-.301.039-.443c-.039.263.052.393.332.336c.027.063.032.11-.062.104l-.253.004q-.026.027-.056-.001");
}

.dmks28fkd {
  fill: var(--svg-color--6f6430, #6f6430);
  d: path("M31.475 25.27c-.104-.2-.03-.412-.05-.619c.091.2.042.412.05.619");
}

.dt6s14bdc {
  fill: var(--svg-color--7b7450, #7b7450);
  d: path("M25.331 31.14c.093.018.208-.047.269.076c-.085-.041-.196.016-.269-.076");
}

.dv2azdb6r {
  fill: var(--svg-color--716940, #716940);
  d: path("M28.924 37.914c.075.078.039.177.049.266l-.007.007c-.169-.058-.107-.164-.053-.269z");
}

.dvray4bge {
  fill: var(--svg-color--615933, #615933);
  d: path("M34.736 38.613c-.053-.031-.053-.077-.048-.13l.192.036c-.027.08-.085.089-.144.094");
}

.dyg04fboi {
  fill: var(--svg-color--8e824f, #8e824f);
  d: path("M31.563 38.769c-.095-.075-.098-.177-.086-.285c.074.081.076.185.086.285");
}

.dzcpnybhi {
  fill: var(--svg-color--5001c0, #5001c0);
  d: path("m33.884 30l.116.187c-.109.162-.258.064-.381.041c-.52-.104-1.041-.19-1.57-.187a7.6 7.6 0 0 0-1.52.191c-.117.024-.257.11-.353-.051q.067-.111.13-.221c.323-.205.699-.18 1.056-.228c.733-.095 1.467-.034 2.189.115c.125.026.246.049.333.153");
}

.e04ow70ee {
  fill: var(--svg-color--7c6c22, #7c6c22);
  d: path("M29.981 38.622c-.084-.127-.08-.254-.005-.383z");
}

.e17mbkb8l {
  fill: var(--svg-color--5e5529, #5e5529);
  d: path("M37.5 36.583q.032-.026.063-.054c.046.013.107-.057.133.005c.022.043-.023.09-.078.104z");
}

.e30f18bel {
  fill: var(--svg-color--8a7d3f, #8a7d3f);
  d: path("M27.744 37.08c.061-.108.102-.236.24-.277c-.135.113.01.21.017.315l.005-.004c-.096.057-.164-.092-.262-.034");
}

.e6iiv2y4y {
  fill: var(--svg-color--787254, #787254);
  d: path("m34.463 37.683l-.212-.032c.084-.083.161-.098.212.032");
}

.e9wkmcmom {
  fill: var(--svg-color--f3c801, #f3c801);
  d: path("M27.374 37.31c-.112-.13.064-.117.097-.166c.134-.217.299-.412.451-.614c.043-.058.084-.044.127-.007c.114.048.076.11.018.171l-.082.104c-.104.074-.13.21-.24.277a6 6 0 0 0-.153.202c-.061.099-.123.169-.218.033m8.325-.23c.156.178.296.365.413.571c.036.048.167.007.12.13l-.046.032c-.091.069-.135-.023-.198-.057c-.185-.212-.303-.477-.517-.668c-.079-.072-.002-.103.049-.132c.144-.079.133.066.179.124m-7.317 1c-.143-.007-.171-.041-.089-.184c.137-.226.249-.467.409-.676c.041-.052.031-.184.159-.102l-.003-.005c.08.048.087.11.046.188c-.062.084-.128.161-.166.258c-.033.079-.109.125-.14.202q-.058.1-.118.198c-.037.036.008.141-.098.121");
}

.eb5wkxbij {
  fill: var(--svg-color--e20b0b, #e20b0b);
  d: path("M31.852 30.745c.244-.149.385-.044.491.152c.046.085.11.178.032.267c-.052.059-.137.024-.201 0c-.104-.041-.178-.12-.185-.233c-.01-.14-.003-.14-.137-.186");
}

.eca_ijb2e {
  fill: var(--svg-color--6d6542, #6d6542);
  d: path("M36.08 26.962c.103-.052.205-.066.342.013c-.143.075-.242.056-.342-.013");
}

.ed_-tmlos {
  fill: var(--svg-color--bba126, #bba126);
  d: path("M32.533 39.09c.03-.065-.035-.106-.041-.162l.263.108c-.027.146-.131.063-.205.064z");
}

.eeiu44nui {
  fill: var(--svg-color--766e46, #766e46);
  d: path("m35.32 25.319l.002-.151c.053.036.164.01.154.106c-.01.084-.104.022-.156.045");
}

.eexyhhb5k {
  fill: var(--svg-color--72693f, #72693f);
  d: path("m27.16 36.26l.045.096l-.156.013l-.078-.006c0-.152.122-.075.189-.103");
}

.ejqm_d-zr {
  fill: var(--svg-color--a2965b, #a2965b);
  d: path("M38.725 32.683c.004.064.016.122.071.163l-.05.034c-.087-.051-.072-.133-.061-.214a.1.1 0 0 0 .04.017");
}

.el7m9r2js {
  fill: var(--svg-color--706430, #706430);
  d: path("m38.531 31.87l-.064.069c-.125-.103-.121-.235-.098-.377c.027-.028.039-.08.096-.047c.019.119-.027.249.066.355");
}

.elkmyob3g {
  fill: var(--svg-color--f2c701, #f2c701);
  d: path("m25.02 30.918l.096.011c.084.061.193-.033.277.045l-.003-.002c.071.082.199-.026.263.077c.068.07.11-.003.159-.029c.095.002.093.054.061.121l.002-.007c-.053.028-.014.145-.118.117c-.051-.02-.113.013-.156-.036c-.065-.111-.19-.01-.269-.079l.007.003c-.08-.07-.191.007-.273-.054l.007.002c-.134-.043-.33-.035-.216-.276l-.003.003c.097-.028.089.102.166.104");
}

.erihlp3su {
  fill: var(--svg-color--3f6101, #3f6101);
  d: path("M33.879 33.435v-.054c.128-.115.287-.089.429-.065c.198.034-.026-.096.044-.099c.15 0 .271.065.385.157q.043.04-.014.061z");
}

.f3b8l45lk {
  fill: var(--svg-color--f5ca00, #f5ca00);
  d: path("M38.1 27.679a.06.06 0 0 1 .025.036c.075.117-.064.102-.092.156c-.084.054-.159.118-.255.153c-.047.03-.126-.028-.162.044q-.127.067-.253.138c-.053.024-.082.115-.16.043a.06.06 0 0 1-.016-.045c-.066-.13.051-.126.117-.159l.665-.434c.08-.05.097.024.131.068");
}

.fcuubqchk {
  fill: var(--svg-color--85762d, #85762d);
  d: path("M25.02 30.918c-.094.023-.109-.071-.167-.104c-.005-.109-.011-.223.06-.319q.044-.04.09.001c.001.141-.105.285.017.422");
}

.fh21t3rme {
  fill: var(--svg-color--7c6f2e, #7c6f2e);
  d: path("M39.22 32.733c-.087.035-.172.079-.271.055c.03-.118-.161-.11-.128-.229c.014-.038.035-.065.08-.036c.12.05.247.087.319.21");
}

.fiwxokb8f {
  fill: var(--svg-color--6f622a, #6f622a);
  d: path("M32.28 25.462q.104.139.217.011q.214 0 .426.004l.009.033c-.017.054-.08.034-.107.068c-.183-.002-.368.014-.547-.01c-.158-.019-.051-.072.002-.106");
}

.fnhxdh6ab {
  fill: var(--svg-color--6a6449, #6a6449);
  d: path("M25.693 28.3q.044.006.083.014c-.004.087-.047.159-.136.125c-.036-.012.005-.102.053-.139");
}

.frb_zyb2n {
  fill: var(--svg-color--5a5335, #5a5335);
  d: path("m26.668 26.896l.109.137c-.07-.007-.15.007-.195-.028c-.028-.018.045-.078.086-.109");
}

.fvr583b1t {
  fill: var(--svg-color--635824, #635824);
  d: path("M38.525 32.361q.004-.03.003-.06a.4.4 0 0 0 .038.048z");
}

.fxar9gb1u {
  fill: var(--svg-color--7d6e28, #7d6e28);
  d: path("m37.772 28.1l-.115.094c0-.048.034-.104-.041-.125c.012-.089.084-.079.146-.087c.047.034.045.075.01.118");
}

.g-izvun6l {
  fill: var(--svg-color--e7bf03, #e7bf03);
  d: path("M32.912 38.14c.095-.097.155-.086.18.055c-.102.117-.128-.014-.18-.055");
}

.g0srzz9xf {
  fill: var(--svg-color--f5ca01, #f5ca01);
  d: path("M38.421 29.423q.129-.122.253-.249c.062-.067.115-.108.176-.004l-.634.693c-.043.024-.068.092-.135.054l-.043-.111c-.027-.063.019-.082.062-.106l.132-.117c.064-.052.073-.172.189-.16");
}

.g16-trnth {
  fill: var(--svg-color--6b6135, #6b6135);
  d: path("M38.95 29.972q-.212-.01-.422-.015c.142-.064.285-.101.422.015");
}

.g5fh_pdnj {
  fill: var(--svg-color--6d653b, #6d653b);
  d: path("M38.1 35.995c-.05-.087-.173-.016-.219-.108q.09-.001.184-.005c.088-.002.088-.002.035.113");
}

.gb6fb_b0g {
  fill: var(--svg-color--edc301, #edc301);
  d: path("M36.697 36.534c-.055-.021-.025-.11-.094-.12c-.034-.061-.176.048-.156-.095c.146-.144.25-.011.361.059c.065.075.024.162.029.244c-.119.081-.078-.085-.14-.088");
}

.gbx-o-j5r {
  fill: var(--svg-color--c5aa2a, #c5aa2a);
  d: path("M36.652 27.13c.006.038-.015.053-.046.058c-.066.021-.113.11-.202.051q-.022-.01-.026-.036c-.019-.151.126-.067.174-.118c.05-.017.077.017.106.051z");
}

.gcjb-r0qq {
  fill: var(--svg-color--f5ca00, #f5ca00);
  d: path("M30.2 37.934c-.085.093-.173.187-.224.306a.63.63 0 0 0 .005.383q.017.018.026.041c.039.013.059.041.045.078c-.014.036-.045.048-.084.036c-.067-.054-.15-.099-.151-.2a.9.9 0 0 1 .003-.453c.039-.201.199-.265.365-.32a.1.1 0 0 0 .027.015q.015.028.016.061a.3.3 0 0 1-.028.053");
}

.gdpozpaiv {
  fill: var(--svg-color--7a6f3a, #7a6f3a);
  d: path("M26.668 36.432c.15 0 .113-.167.202-.221c-.007.078.062.106.101.154q.045-.032.078.006a.6.6 0 0 1-.32.108c-.057.029-.065-.002-.061-.047");
}

.gebjc_-ic {
  fill: var(--svg-color--75682e, #75682e);
  d: path("M33.667 38.577a.9.9 0 0 1-.104-.414c.068.028.043.164.159.135c.036.023.095.002.119.054c-.094.047-.208.077-.174.225");
}

.gf5eeib5k {
  fill: var(--svg-color--f5b901, #f5b901);
  d: path("M31.463 32.666c.109.173.311.206.469.303c.066.044.178.036.186.152c-.719-.108-1.246-.65-1.225-1.256c.176-.007.185.149.246.254c.06.096.109.194.163.294c.074.074.194.115.161.253");
}

.gfx40ubjf {
  fill: var(--svg-color--7e7138, #7e7138);
  d: path("M28.23 36.631c.093.076.2.128.268.243c.067.118-.01.168-.076.246c-.003-.201-.135-.31-.263-.42q-.017-.09.071-.069");
}

.gh10sebnn {
  fill: var(--svg-color--706844, #706844);
  d: path("M36.994 35.834c.103.023.217.009.301.101c-.01.043-.046.064-.079.089a.16.16 0 0 1-.082.034z");
}

.gibdx_mcn {
  fill: var(--svg-color--91e56d, #91e56d);
  d: path("M33.29 31.14h1.035l-.001.046h-1.028c-.018-.008-.021-.018-.018-.028q.005-.017.012-.018");
}

.gieuhuoas {
  fill: var(--svg-color--f9cd01, #f9cd01);
  d: path("M25.482 33.971q-.02-.022-.044-.043a.42.42 0 0 1 .003-.292l.047-.045c.092-.029.181-.053.268.012c.13.118.145.238.021.368a.45.45 0 0 1-.295 0");
}

.gk51zhtkt {
  fill: var(--svg-color--b79a15, #b79a15);
  d: path("M33.93 37.873q.029-.064.056-.132c.02-.031.036-.026.049.005c.035.072.074.149-.047.181c-.019-.017-.041-.036-.058-.054");
}

.gkjqhtb3b {
  fill: var(--svg-color--1fb6fe, #1fb6fe);
  d: path("M33.451 33.75a.32.32 0 0 1 .161-.157v.002q-.012.146-.155.162z");
}

.gn0gwcb5s {
  fill: var(--svg-color--1dbbfe, #1dbbfe);
  d: path("M33.457 33.757c-.166.158-.351 0-.526-.007h.521z");
}

.gnktfvbdn {
  fill: var(--svg-color--6d6438, #6d6438);
  d: path("M37.14 36.795c-.106-.023-.237.055-.321-.07c.101.043.229-.022.321.07");
}

.grh7cvuoo {
  fill: var(--svg-color--968328, #968328);
  d: path("m39.16 30.707l.009.106c-.05.023-.12.103-.15.014c-.028-.085.069-.106.141-.12");
}

.gvbii6bnn {
  fill: var(--svg-color--5f562d, #5f562d);
  d: path("m34.463 38.07l-.007.041q-.016-.007-.027-.018l.041-.02z");
}

.gxy88xv-i {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M25.17 30.338c.07.034.059.1.061.157c.029.024.064.035.094.055a.2.2 0 0 1 .06.093a.3.3 0 0 1-.022.194a.23.23 0 0 1-.235.147a.3.3 0 0 1-.126-.039c-.141-.135-.093-.282-.035-.434c.019-.115.14-.108.203-.173");
}

.h2m5sbb5s {
  fill: var(--svg-color--f1c701, #f1c701);
  d: path("M26.932 36.91c-.017-.02-.036-.036-.053-.057c-.024-.054.003-.091.046-.121q.194-.175.388-.354c0-.051.035-.08.066-.115a.7.7 0 0 1 .095-.102c.09-.008.188-.032.259.054c.035.063-.016.074-.055.094a85 85 0 0 0-.631.58c-.03.055-.071.043-.115.021");
}

.h6dztrbgr {
  fill: var(--svg-color--746628, #746628);
  d: path("m36.85 36.64l-.031-.009q-.007-.127-.01-.253c.119.071.057.171.041.262");
}

.h7uqzybof {
  fill: var(--svg-color--6e6640, #6e6640);
  d: path("M28.794 38.14c-.069-.082-.036-.179-.041-.27l.001-.005c.13.031.107.125.094.219a.1.1 0 0 1-.054.056");
}

.ha9z0znhd {
  fill: var(--svg-color--6c6338, #6c6338);
  d: path("M38.26 30.22c.012.053-.015.117.05.149c0 .112.03.228-.047.337c-.073-.157-.101-.317-.003-.486");
}

.hdm0a6b4n {
  fill: var(--svg-color--ae9005, #ae9005);
  d: path("M35.32 38.15c-.094-.026-.14-.096-.182-.171c.132-.072.165-.043.182.171");
}

.hfpii4cxd {
  fill: var(--svg-color--1cbcfe, #1cbcfe);
  d: path("M30.622 34.13c.093 0 .187-.004.279-.025c-.087.09-.179.116-.279.025");
}

.hgg2gdbpl {
  fill: var(--svg-color--7e764d, #7e764d);
  d: path("M34.463 25.15q.024.052.043.106c.021.056 0 .132-.051.104c-.103-.055-.042-.141.008-.21");
}

.hinsp-rcu {
  fill: var(--svg-color--746a3e, #746a3e);
  d: path("M26.513 28.681c.077.153.151.307-.058.422l.005.004l-.013-.356c-.016-.061.011-.077.066-.07");
}

.hpyi2mblk {
  fill: var(--svg-color--877833, #877833);
  d: path("M26.344 36.04c.139-.099.203-.306.424-.288c-.053.187-.229.25-.355.361c-.032-.002-.051-.02-.066-.045z");
}

.hqx0rfqkk {
  fill: var(--svg-color--786d38, #786d38);
  d: path("M37.988 27.818c.018-.071.129-.015.137-.104c.1.034.12.118.141.207c.025.051-.004.072-.045.087c-.121-.007-.181-.096-.233-.19");
}

.i_ok185dp {
  fill: var(--svg-color--6f611e, #6f611e);
  d: path("M36.23 37.78q-.063-.066-.12-.13c.072 0 .151-.018.188.071c.003.008-.045.04-.068.059");
}

.i394qvbdy {
  fill: var(--svg-color--786c34, #786c34);
  d: path("m27.418 36.31l-.105.067l-.107-.02c-.03-.026-.032-.063-.045-.096c.018-.126.121.012.162-.052q.118-.02.095.101");
}

.i8led9bqb {
  fill: var(--svg-color--716944, #716944);
  d: path("m27.681 26.12l-.108-.115c.029-.043.06-.099.115-.061c.078.055-.024.116-.007.176");
}

.i9d0wdbxj {
  fill: var(--svg-color--867735, #867735);
  d: path("M26.513 27.541a.28.28 0 0 0-.208-.021l-.007-.063c.085-.005.179-.034.215.084");
}

.ia_045zit {
  fill: var(--svg-color--1ac0fe, #1ac0fe);
  d: path("m35.857 34.1l-.199-.095c.086-.06.129-.02.199.095");
}

.ib-rtub4k {
  fill: var(--svg-color--605523, #605523);
  d: path("m37.4 36.792l.077.01l-.118.108c-.038-.104-.168-.034-.22-.117z");
}

.ibfgn0bgu {
  fill: var(--svg-color--89792d, #89792d);
  d: path("M26.4 27.936q.074-.089.15-.173l.08.015l-.08.212c-.052-.007-.114.004-.15-.054");
}

.ihkg6mw0l {
  fill: var(--svg-color--7d7034, #7d7034);
  d: path("m28.23 26.877l-.004-.119c.036-.025.088-.086.113-.006c.033.084-.059.093-.109.125");
}

.ijolx--_j {
  fill: var(--svg-color--726631, #726631);
  d: path("m32.16 25.21l.014-.441c.07.149.112.296-.014.441");
}

.ikx50uv5h {
  fill: var(--svg-color--716c55, #716c55);
  d: path("M37.13 35.744c-.063-.017-.125-.028-.163.045c-.039-.023-.068-.073-.025-.098c.066-.036.147-.043.188.053");
}

.ilspkrb5a {
  fill: var(--svg-color--7c744f, #7c744f);
  d: path("M36.955 26.28c-.105.069-.174.066-.229-.006c-.011-.017-.009-.06.003-.065c.083-.046.137.018.226.071");
}

.in28rk_ri {
  fill: var(--svg-color--09efea, #09efea);
  d: path("m30.557 32.471l-.105-.21c.133-.065.182-.22.297-.304c-.004.194-.107.352-.192.514");
}

.is63r5b1b {
  fill: var(--svg-color--1dbbfe, #1dbbfe);
  d: path("M31.747 33.962c.08.019.157.04.21.11c-.094.012-.173-.008-.217-.102z");
}

.iuqjxz_8s {
  fill: var(--svg-color--7d754e, #7d754e);
  d: path("M33.776 38.859q-.002-.013-.008-.025c.049-.086.134-.062.21-.065c.064-.03.095.009.122.062a.33.33 0 0 1-.324.028");
}

.iywnp160a {
  fill: var(--svg-color--68603c, #68603c);
  d: path("m32.873 39.04l.303-.185c-.059.178-.138.234-.253.249c-.033-.008-.04-.039-.05-.064");
}

.j_0yt57tg {
  fill: var(--svg-color--3e5e00, #3e5e00);
  d: path("M31.959 33.33c-.088.014-.161-.02-.257-.095c.13-.014.199.026.255.097z");
}

.j_8nulbcl {
  fill: var(--svg-color--6e632e, #6e632e);
  d: path("M26.19 35.07c-.04.018-.093.002-.106.061c-.098.026-.181-.084-.278-.029c-.066-.065-.135 0-.204-.014c-.049-.061-.126-.128.039-.121l.393.02c.05.028.105.056.156.083");
}

.j_kgbac6y {
  fill: var(--svg-color--5f593c, #5f593c);
  d: path("M26.925 36.732q-.022.062-.046.121c-.046-.025-.106-.059-.087-.109c.023-.067.087-.026.133-.012");
}

.j61z68bjo {
  fill: var(--svg-color--f2c700, #f2c700);
  d: path("M39.21 30.596q.056.061.111.125c.02.141-.087.082-.15.093c-.035-.032-.035-.068-.009-.106c.012-.039 0-.089.048-.112");
}

.j7buelznk {
  fill: var(--svg-color--16cbfe, #16cbfe);
  d: path("m31.795 33.547l.003.044h-.436c.144-.072.287-.048.433-.044");
}

.ja3p_ebog {
  fill: var(--svg-color--f8cc00, #f8cc00);
  d: path("M38.688 34.11c.012.181-.139.231-.255.218a.25.25 0 0 1-.226-.272c.009-.156.153-.217.25-.201c.106.015.265.071.231.255");
}

.jbjhttbuv {
  fill: var(--svg-color--82794c, #82794c);
  d: path("M33.29 37.938c.09.047.133.116.104.218c-.034-.07-.131-.114-.104-.218");
}

.jcw_j7bvd {
  fill: var(--svg-color--827953, #827953);
  d: path("M27.14 35.566c-.058-.074-.128-.098-.214-.052v-.228c.11.083.21.142.214.28");
}

.jez-8_bet {
  fill: var(--svg-color--5c5538, #5c5538);
  d: path("M38.1 29.699c-.023.037-.041.071-.062.106c-.054-.036-.089-.108-.061-.149c.053-.069.075.041.123.043");
}

.ji6r_8bek {
  fill: var(--svg-color--85783a, #85783a);
  d: path("M25.19 29.474q.026.029.057.058c.061.107.032.212-.009.317l-.188-.045c.037-.116.043-.241.14-.33");
}

.jjngsubpu {
  fill: var(--svg-color--f4c900, #f4c900);
  d: path("M32.43 38.72c-.061.092.052.138.063.212c.053.043.119.084.041.162c-.177-.054-.295-.162-.312-.355a.6.6 0 0 1 .002-.361c-.009-.093.075-.127.126-.181c.022-.024.043-.081.099-.035c.067.055-.015.089-.015.132a.9.9 0 0 0-.004.426");
}

.jkf2h3baj {
  fill: var(--svg-color--1eb9fe, #1eb9fe);
  d: path("M28.87 34.22c-.128.094-.2.06-.301.067c.095-.095.171-.034.301-.067");
}

.jmseg9beu {
  fill: var(--svg-color--f4c901, #f4c901);
  d: path("M26.351 29.26c-.128.147-.276.106-.414.038c-.138-.069-.263-.158-.396-.238c-.036-.074-.236 0-.156-.178a1 1 0 0 1 .038-.1c.123-.059.098.1.172.116c.217.087.378.316.648.268c.033.033.133-.005.108.094");
}

.jo-wtlf8h {
  fill: var(--svg-color--65ec99, #65ec99);
  d: path("M32.862 31.771a.6.6 0 0 1-.245-.275c.147.104.252.142.243.279z");
}

.jtkewxbbv {
  fill: var(--svg-color--887c43, #887c43);
  d: path("M33.424 38.35c.131.064.074.187.084.288c-.074-.082-.046-.195-.084-.288");
}

.k_rjucckx {
  fill: var(--svg-color--797047, #797047);
  d: path("M34.522 25.03c.063.071.134.141.101.25l-.117-.024c-.099 0-.061-.058-.043-.106c0-.05.016-.091.059-.12");
}

.k5u-47bvk {
  fill: var(--svg-color--796b29, #796b29);
  d: path("M38.26 29.322c-.121-.088-.225-.212-.4-.155c-.049.013-.087-.023-.079-.08c.007-.043.048-.037.082-.037c.327-.002.657-.013.983 0c.143.007.061.078.004.12c-.191.01-.234.268-.437.266a.14.14 0 0 1-.026-.067c-.002-.046.051-.109.029-.119c-.065-.031-.1.052-.156.072");
}

.ka0v6iaai {
  fill: var(--svg-color--f7f7f6, #f7f7f6);
  d: path("M26.884 28.2c-.169.024-.257-.086-.333-.212c-.047-.095-.009-.171.058-.24a.25.25 0 0 1 .13-.041c.114-.006.217.014.285.117c.063.151.014.272-.099.376z");
}

.kb68azpux {
  fill: var(--svg-color--908241, #908241);
  d: path("M27.924 27.08c-.005.182-.13.251-.292.333c0-.146.087-.212.144-.289c.05-.012.074-.108.148-.044");
}

.kdesd-hay {
  fill: var(--svg-color--7be883, #7be883);
  d: path("M32.862 31.09q.003.025.002.051h-.335c.144-.087.24-.046.333-.051");
}

.ki0hl23ip {
  fill: var(--svg-color--152011, #152011);
  d: path("m28.359 33.33l.283-.041a.15.15 0 0 1-.027.085c-.094.028-.188.004-.281-.015q.001-.025.025-.029");
}

.ki6w7kben {
  fill: var(--svg-color--416000, #416000);
  d: path("M32.28 33.17c.146-.074.225.041.32.111c-.122.008-.215-.065-.32-.111");
}

.kklw3kbqg {
  fill: var(--svg-color--e5e5e5, #e5e5e5);
  d: path("M29.773 25.483q-.106.052-.214.108c-.106-.117-.037-.251-.033-.376c.08.091.195.153.247.268");
}

.kllft4a3g {
  fill: var(--svg-color--7b6e31, #7b6e31);
  d: path("M29.13 37.529c.004.145-.103.169-.212.192c-.055.011-.111.024-.109-.063l.003-.007c.129.018.238-.013.318-.122");
}

.km3m8rvwg {
  fill: var(--svg-color--70673a, #70673a);
  d: path("M25.385 28.886c-.025.128.141.087.156.178c-.084-.035-.162.02-.248.029c-.007-.095.034-.154.092-.207");
}

.knblg2bpz {
  fill: var(--svg-color--736628, #736628);
  d: path("M31.994 24.841c.11.117.11.238.009.361z");
}

.kttybh77k {
  fill: var(--svg-color--fcfcfb, #fcfcfb);
  d: path("M25.23 29.849c-.112-.11.016-.212.009-.317c.107.005.219-.01.313.058c.083.141.077.253-.099.315z");
}

.ku3ml56su {
  fill: var(--svg-color--6a6137, #6a6137);
  d: path("M29.339 38.559c.134.023.087-.13.158-.164c-.017.098.046.169.109.262a.37.37 0 0 1-.267-.098");
}

.ky11mebgv {
  fill: var(--svg-color--f2c800, #f2c800);
  d: path("M30.02 25.744q-.052-.07-.099-.14c-.031-.08-.121-.056-.174-.102a2 2 0 0 1-.283-.272a.3.3 0 0 1-.043-.105c.011-.053-.037-.14.075-.14c.278.208.477.507.762.71c.061.044-.026.074-.055.108c-.079.035-.137.011-.183-.059");
}

.l_37ylb8a {
  fill: var(--svg-color--4363fd, #4363fd);
  d: path("M28.908 32.413h.902c.069.188-.063.308-.171.411c-.301.29-.651.489-1.075.525c-.069-.006-.142.026-.205-.02q.276-.458.549-.916");
}

.l1dhfqb1h {
  fill: var(--svg-color--fcfcfc, #fcfcfc);
  d: path("M38.26 29.322c-.017-.266.182-.128.293-.169c.008.117-.107.148-.132.23c-.056.034-.111.034-.161-.012z");
}

.l3jgx7bbh {
  fill: var(--svg-color--26a5fe, #26a5fe);
  d: path("M30.4 34.02h-.395c.173-.109.285-.171.406-.016z");
}

.l4eor6b4o {
  fill: var(--svg-color--d7b518, #d7b518);
  d: path("M25.6 35.09c.074-.085.143-.095.204.014c-.025.029-.079-.024-.092.031c-.065.046-.077-.023-.112-.047z");
}

.l6bxbobfn {
  fill: var(--svg-color--82763f, #82763f);
  d: path("M26.344 36.27a.56.56 0 0 1-.201-.246c.082-.058.133.051.201.017l.016.02c.018.07.038.141-.016.209");
}

.leg6h1bwm {
  fill: var(--svg-color--e2bb03, #e2bb03);
  d: path("M25.437 30.701q-.057-.047-.114-.098l-.036-.034c.077-.005.164-.061.224.041q-.04.046-.074.091");
}

.li-80dbaf {
  fill: var(--svg-color--81722d, #81722d);
  d: path("m35.988 37.756l.198.057c-.114.148-.177.127-.198-.057");
}

.li8xymbwo {
  fill: var(--svg-color--82763d, #82763d);
  d: path("m35.688 36.843l.061.054q-.024.092-.05.183c-.055-.048-.085-.13-.179-.123a.23.23 0 0 1 .168-.114");
}

.lnw_t5b-m {
  fill: var(--svg-color--4df0b1, #4df0b1);
  d: path("M32.17 28.513h-.111q.002-.107.01-.213c.054-.133-.018-.279.042-.409c.107.198.025.415.059.622");
}

.lo-b_wbhh {
  fill: var(--svg-color--665e38, #665e38);
  d: path("M31.422 39.08c.07.012.15.063.202-.036c.096.012.109.068.022.097c-.065.021-.178.054-.224-.061");
}

.lo66k7tqp {
  fill: var(--svg-color--766d48, #766d48);
  d: path("m30.2 37.934l-.005-.067c.065-.076.156-.045.234-.058l.034-.007c.077.005.162 0 .156.116l.002-.004z");
}

.ltdjgxbin {
  fill: var(--svg-color--fd0d01, #fd0d01);
  d: path("M32.17 28.513c.33.019.655.057.951.226c.077.073.164.143.174.263c-.088.089-.197.063-.302.054a10 10 0 0 0-1.758.007c-.128.012-.288.075-.356-.118l.159-.219c.322-.15.664-.21 1.021-.212q.055-.04.111-.001");
}

.luq9xmbim {
  fill: var(--svg-color--726630, #726630);
  d: path("M25.286 30.569c-.028-.017-.062-.03-.058-.074c.089.003.181-.008.268.009c.077.013.065.065.014.106c-.082.007-.151-.026-.224-.041");
}

.lv2xqbbmk {
  fill: var(--svg-color--7a6b23, #7a6b23);
  d: path("M32.589 24.562a.05.05 0 0 0-.003-.041c.068-.056.148-.021.222-.032c.091.008.183-.018.271.021c.068.106.06.195-.053.266c-.054-.255-.307-.111-.437-.214");
}

.m4tc0_7xf {
  fill: var(--svg-color--787150, #787150);
  d: path("m29.393 26.01l.05.002q.035-.008.069-.013c.072.104-.008.111-.08.131c-.037.012-.078.062-.099-.013c-.014-.051.032-.075.06-.107");
}

.m5soovbiw {
  fill: var(--svg-color--897a35, #897a35);
  d: path("M25.556 29.589c.056.002.102-.009.108-.075c.143.138-.027.342.101.484q-.155-.049-.306-.094c0-.114.073-.207.097-.315");
}

.m7576zbiv {
  fill: var(--svg-color--6da600, #6da600);
  d: path("m28.615 33.374l.024-.085c.496-.151.964-.342 1.171-.876q.118-.241.231-.484c.104.004.132.086.156.159c.162.526.525.83.993.944c-.141-.065-.357-.111-.511-.275c-.08-.084-.165-.164-.157-.294c.022-.192.168-.329.225-.506l.145-.092a.25.25 0 0 1 .062.115c.111.645.569.926 1.145 1.082q.093.028.187.049c.114.038.222.087.332.128c.048.031.104.053.095.125c-.232.074-.468.053-.702.005c-.055-.063-.139-.066-.199-.111c-.004.077.208-.01.115.145c-.279.006-.559 0-.836.002h-.902c-.364-.014-.725.027-1.085-.021q-.244-.006-.489-.01");
}

.mhszp0qvm {
  fill: var(--svg-color--71642b, #71642b);
  d: path("M30.832 38.765c.067-.091.043-.255.217-.258c.086.034.205.026.227.156c-.041.066-.121.011-.171.052c-.096-.011-.153.046-.203.117c-.06.013-.088-.002-.07-.067");
}

.mk4o1acut {
  fill: var(--svg-color--70642c, #70642c);
  d: path("M28.913 26.395c-.021.053-.063.048-.104.043c-.043-.004-.096-.023-.066-.075c.012-.021.073-.025.111-.03c.041-.006.06.021.059.062");
}

.mldi_7bhz {
  fill: var(--svg-color--7b7453, #7b7453);
  d: path("m25.756 33.603l-.268-.012c.094-.068.186-.109.268.012");
}

.mmkkn4bwk {
  fill: var(--svg-color--f7cc00, #f7cc00);
  d: path("M31.902 25.424c.046-.07.025-.167.101-.222c.052-.123.063-.244-.009-.361c-.06-.082-.104-.166-.092-.272c.142-.002.193.114.27.199c.028.149.061.297-.014.441c-.049.114-.076.256-.256.215");
}

.mqxh9abgx {
  fill: var(--svg-color--7e702e, #7e702e);
  d: path("M28.18 37.23c-.003.091-.032.162-.142.188l-.01-.249c.061-.008.118-.003.152.061");
}

.mur8xxm0p {
  fill: var(--svg-color--887931, #887931);
  d: path("M34.31 37.811c.102-.043.178-.023.214.088c-.062.021-.055.076-.057.124l.007-.004c-.058-.068-.173-.089-.164-.208");
}

.mx3abbcne {
  fill: var(--svg-color--716530, #716530);
  d: path("M36.66 36.848c.074.013.158-.018.212.061l-.264.019l-.012-.025c-.003-.049.012-.075.064-.055");
}

.mxxko4xkl {
  fill: var(--svg-color--76661a, #76661a);
  d: path("M26.351 29.26q-.054-.045-.107-.094l.217-.063l-.005-.004c.013.085.021.166-.105.161");
}

.mzclkiawr {
  fill: var(--svg-color--3e5f00, #3e5f00);
  d: path("M32.924 33.426c-.001-.016-.006-.03-.006-.045c.141-.12.312-.076.47-.065c.132.011.036-.071.059-.102c.19-.091.317.02.442.141a.07.07 0 0 1-.01.08z");
}

.n_evikbtl {
  fill: var(--svg-color--6da600, #6da600);
  d: path("m33.443 33.22l-.157-.053c-.062-.041-.139-.041-.202-.075c-.258-.107-.555-.151-.682-.46c-.003-.107.098-.153.143-.233c.082-.173.128-.368.268-.515l.027.023a.2.2 0 0 1 .027.046c.125.623.521.974 1.111 1.14c.069.033.146.038.217.074l.156.053c.061.044.116.09.212.164h-.685c-.143-.063-.266-.171-.435-.164");
}

.n_nj63gtl {
  fill: var(--svg-color--1dbbfe, #1dbbfe);
  d: path("M30.412 34.01c.076.031.161.043.21.117c-.095.013-.171-.017-.222-.102z");
}

.n2oqopkls {
  fill: var(--svg-color--1eb9fe, #1eb9fe);
  d: path("M29.828 34.27c.018-.108.063-.147.134-.169c.012.089-.048.122-.134.169");
}

.n3wpa6bkt {
  fill: var(--svg-color--e8bf00, #e8bf00);
  d: path("m30.2 37.818l.261-.006c-.075.08-.174.037-.264.054q0-.023.003-.048");
}

.n8vwtlfdz {
  fill: var(--svg-color--05f2ef, #05f2ef);
  d: path("M33.494 32.26c.02.056-.02.097-.041.141c-.037.079-.106.079-.181.072c-.161-.039-.193-.191-.266-.309a1.6 1.6 0 0 0-.184-.263l-.011-.019c.017-.037.031-.073.05-.11l-.002.002a.46.46 0 0 1 .257.216c.104.038.162.12.215.208z");
}

.n8z1vkbtg {
  fill: var(--svg-color--786c36, #786c36);
  d: path("M34.25 37.647c.021.058.038.11.057.167c-.063-.059-.139-.059-.216-.054l.006.005c-.002-.111.076-.115.153-.118");
}

.nbgi7dbzk {
  fill: var(--svg-color--f0c601, #f0c601);
  d: path("M28.22 25.966c.114.154.144.388.388.422c.017.002.039.033.041.053c.007.043-.029.058-.067.058c-.228.012-.383-.105-.474-.302c-.086-.194-.159-.393.066-.553c.057.102-.013.22.046.322m8.477 11.374l-.414-.477c-.035-.093-.132-.143-.168-.236c.003-.108.063-.155.17-.147c.07.061.098.152.152.227c.039.068.102.113.159.164c.017.012.02.025.019.038q-.001.022-.002.021c.027.113.113.181.195.251c.039.038.152-.003.121.111l-.103.098c-.062.032-.095-.009-.129-.05");
}

.nd_4asmbx {
  fill: var(--svg-color--81784d, #81784d);
  d: path("M35.1 25.524c0-.076.029-.117.108-.097l-.003-.004q.045.122-.046.22c-.049-.025-.088-.055-.059-.119");
}

.ndlje-bbc {
  fill: var(--svg-color--1fb5fe, #1fb5fe);
  d: path("M29.659 33.819h.316c-.127.07-.218.034-.316 0");
}

.nfyzklbzc {
  fill: var(--svg-color--eaeae9, #eaeae9);
  d: path("M26.19 35.07c.08.06.226-.132.267.074c-.02.084-.123.084-.161.151q-.078.068-.155.006l-.057-.171c-.003-.083.052-.068.106-.06");
}

.ng_20ybpy {
  fill: var(--svg-color--6b6237, #6b6237);
  d: path("m32.814 24.51l-.229.011c-.152-.032-.222.02-.205.188c.014.11-.002.223-.004.336q-.011.038-.041.008c-.041-.188.071-.4-.114-.584h.577q.031.004.029.022c-.004.01-.008.019-.013.019");
}

.ngf0nj-fj {
  fill: var(--svg-color--fed100, #fed100);
  d: path("M25.76 32.25c.058.041.06.077-.004.112q-.101 0-.202-.004a1.8 1.8 0 0 0-.644.004l.002.006c-.074-.034-.053-.102-.053-.159q.024-.004.051-.005c.278.102.567.037.85.046");
}

.njmkf9_jl {
  fill: var(--svg-color--6b612e, #6b612e);
  d: path("M30.832 38.765q.036.032.069.067c.03.237-.098.237-.314.175a.6.6 0 0 0 .245-.242");
}

.nmek-raev {
  fill: var(--svg-color--f5c900, #f5c900);
  d: path("M31.475 25.27q.002.074.008.146c.023.043.105.078.026.141c-.077-.009-.179.052-.218-.076v-.261c-.014-.144.025-.291-.027-.432a.43.43 0 0 0-.1-.25c.225-.079.263-.062.261.12v-.007c.067.202-.02.416.05.619");
}

.nq-p6ru4p {
  fill: var(--svg-color--625c3e, #625c3e);
  d: path("M38.32 32.938c-.092.078-.081.153.01.226c-.023.026-.041.069-.071.077c-.08.024-.061-.054-.051-.075c.039-.082-.092-.242.112-.246z");
}

.nq1gyhyrz {
  fill: var(--svg-color--f3c901, #f3c901);
  d: path("M39.22 32.733c.194.117.005.141-.049.158c-.282.097-.564.182-.849.272c-.167-.046-.097-.139-.05-.227c.099-.035.211.024.304-.041h-.005a.23.23 0 0 1 .122-.064q.05-.016.099-.037q.084-.038.17-.061c.087-.013.173-.031.258-.001");
}

.nrdq6-1xk {
  fill: var(--svg-color--6e6125, #6e6125);
  d: path("M28.22 25.966c-.089-.097-.034-.214-.046-.322c.113.092.024.216.046.322");
}

.nsr25my4l {
  fill: var(--svg-color--f6ca00, #f6ca00);
  d: path("M38.95 29.972c.049.065.2.046.161.171c-.018.053-.104.053-.156-.002c-.104-.087-.211-.048-.324-.023a1.1 1.1 0 0 0-.324.253c-.125-.015-.064-.089-.05-.149c.009-.171.162-.196.271-.264c.142-.027.283-.051.422.014");
}

.nt6g6_nyk {
  fill: var(--svg-color--5d552b, #5d552b);
  d: path("m34.36 25.531l-.043-.023q.015-.009.031-.016q.002.024.009.043z");
}

.nyh2v3srn {
  fill: var(--svg-color--6f6431, #6f6431);
  d: path("M39.38 31.19c-.262.118-.538.031-.806.051c.262-.105.539-.017.806-.051");
}

.nzm4a4bkr {
  fill: var(--svg-color--1eb8fe, #1eb8fe);
  d: path("M28.326 33.805v-.055q.194-.002.389-.002v.057z");
}

.o_d0-wb3a {
  fill: var(--svg-color--1fb7fe, #1fb7fe);
  d: path("m31.957 34.07l.335-.056c-.147.095-.229.165-.335.056");
}

.o_etcxbsu {
  fill: var(--svg-color--1cbdfe, #1cbdfe);
  d: path("M33.29 34.02c.154-.133.348.017.51-.07c-.15.154-.339.031-.502.076z");
}

.o0srk9bqs {
  fill: var(--svg-color--95811f, #95811f);
  d: path("m26.528 27.558l.148.044q.023.006.046.017l.006.149q-.047.003-.098.01q-.034.028-.077.005c-.049-.07-.098-.141-.025-.225");
}

.o4itg_wcw {
  fill: var(--svg-color--736d55, #736d55);
  d: path("M30.19 37.804c.092-.08.185-.057.278-.002l-.005.011c-.086.042-.173.032-.261.006z");
}

.o5b_jobcj {
  fill: var(--svg-color--efc504, #efc504);
  d: path("M28.04 26.866q-.23-.285-.463-.57c-.003-.087-.146-.087-.117-.193l.109-.096c.111-.029.067.08.108.115c.151.236.357.427.54.636c.031.039.027.078.004.119l-.05.046c-.065.028-.095-.02-.131-.057");
}

.o7q9w4ejw {
  fill: var(--svg-color--70642c, #70642c);
  d: path("M25.02 29.907c.061.091.21.002.256.125c-.065-.084-.269.114-.256-.125");
}

.o8nw70b8y {
  fill: var(--svg-color--847739, #847739);
  d: path("m38.19 27.996l.079-.074c.094.258.085.302-.071.386c.043-.073.123-.143.008-.223q-.043-.04-.016-.089");
}

.obp4udb3r {
  fill: var(--svg-color--f7f6f6, #f7f6f6);
  d: path("M36.398 36.744c-.062-.08-.13-.156-.113-.268l.052-.056c.074-.058.159-.061.245-.053a.24.24 0 0 1 .154.14a.26.26 0 0 1-.021.199a.3.3 0 0 1-.044.066c-.102.104-.189.041-.273-.028");
}

.ocl8yrlzw {
  fill: var(--svg-color--f6b901, #f6b901);
  d: path("M34.987 33.07c-.351.1-.624-.114-.853-.295c-.263-.2-.401-.525-.401-.88c.148-.035.169.09.219.175c.066.11.126.227.189.34c.091.29.333.416.583.534c.09.039.176.085.263.126");
}

.oe-g602cf {
  fill: var(--svg-color--edebde, #edebde);
  d: path("M33.03 24.775c-.002.053-.009.104-.055.14c-.015.056-.058.073-.109.082c-.376-.009-.388-.02-.375-.347a.18.18 0 0 1 .087-.113c.184.02.424-.072.452.238");
}

.oegl06bwv {
  fill: var(--svg-color--937d16, #937d16);
  d: path("M32.808 25.05c.046-.021.06-.061.062-.104l.103-.032c.017.082.05.181-.036.231c-.068.04-.095-.052-.129-.095");
}

.ogsln1ckz {
  fill: var(--svg-color--888473, #888473);
  d: path("M25.849 31.731c.023-.052.019-.093-.035-.124c.006-.05-.021-.107.036-.138c.036-.018.074.015.068.049c-.014.073.084.186-.069.213");
}

.okj2pv4om {
  fill: var(--svg-color--1fb6fe, #1fb6fe);
  d: path("m30.676 34.473l-.408-.092c.178-.07.267-.005.408.092");
}

.oq6hhfrdl {
  fill: var(--svg-color--706636, #706636);
  d: path("M38.08 29.917q.066-.029.135-.054c-.02.051.009.128-.058.149c-.072.02-.058-.055-.077-.095");
}

.oru17m-cm {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 24h64v16H0z");
}

.os78g6bel {
  fill: var(--svg-color--8a7f4c, #8a7f4c);
  d: path("M34.818 25.311c-.094-.075-.096-.178-.082-.286c.076.082.069.186.082.286");
}

.otiktj-hg {
  fill: var(--svg-color--746c42, #746c42);
  d: path("m33.559 37.925l-.056-.013c.013-.165.136-.082.217-.102c.029.03.087.011.107.056c-.078.08-.181.044-.268.059");
}

.owl2b-b7t {
  fill: var(--svg-color--f7cb00, #f7cb00);
  d: path("m34.68 25.424l-.057-.145c-.035-.082-.148-.133-.101-.25c.007-.054-.033-.131.063-.139c.092-.004.142.044.15.134c.032.094.027.199.082.286c.007.03.018.058.023.089c.033.093.029.197.082.286c.086.136.165.272.022.422c-.11.047-.055-.084-.108-.098v.004c-.044-.064-.001-.166-.085-.217l-.021-.135c-.034-.076-.015-.165-.051-.237");
}

.oxjqouzya {
  fill: var(--svg-color--e4bc03, #e4bc03);
  d: path("M38.564 30.922c-.084.078-.209.089-.228-.02c-.022-.138.153-.087.228-.141c.095-.028.189-.061.285.003l-.004-.005c.03.036.027.077.006.118c-.09.047-.198-.014-.287.045");
}

.oyhsv6qpe {
  fill: var(--svg-color--6da600, #6da600);
  d: path("M33.443 33.22c.06.044.118.09.213.164h-.738l-.212-.055c-.043 0-.082-.008-.106-.047c-.107-.033-.197-.128-.32-.113c-.058-.002-.119.01-.162-.045c-.153-.094-.324-.149-.481-.238c-.081-.046-.181-.08-.183-.201c.014-.124.102-.199.183-.281c.096-.167.104-.383.282-.502a.2.2 0 0 1 .051.09c.132.6.516.942 1.102 1.074c.068.027.146.034.219.049c.062.018.121.043.152.105");
}

.ozvfyib9v {
  fill: var(--svg-color--736938, #736938);
  d: path("M25.393 30.974c-.094-.002-.195.031-.277-.045a.23.23 0 0 0 .225-.11c.051-.009.084.004.053.063z");
}

.p_r0gc4zq {
  fill: var(--svg-color--8a7c38, #8a7c38);
  d: path("m38.465 31.516l-.096.047c-.017-.108-.021-.212.106-.264q.001.083.005.162c-.004.019-.011.034-.015.055");
}

.p0p59nrae {
  fill: var(--svg-color--86762b, #86762b);
  d: path("m29.563 25.64l-.003-.048c.044-.089.121-.117.214-.108c.08 0 .141.026.15.121q-.181.019-.361.035");
}

.p0xhbe13u {
  fill: var(--svg-color--847c55, #847c55);
  d: path("M36.404 27.24q.101-.027.202-.051c-.061.041-.075.253-.202.051");
}

.p1--7zv7p {
  fill: var(--svg-color--726630, #726630);
  d: path("m26.19 27.619l-.065-.064l.113-.124q.03.015.058.026a.08.08 0 0 1 .026.065c-.019.068-.053.113-.132.097");
}

.p2d72acqh {
  fill: var(--svg-color--a4890d, #a4890d);
  d: path("M35.826 36.736c.057.02.167 0 .078.117l-.155.043q-.051-.002-.061-.054c.035-.05.07-.101.138-.106");
}

.p51vv7b3x {
  fill: var(--svg-color--796e3f, #796e3f);
  d: path("M32.43 38.72a.43.43 0 0 1 .004-.427c0 .143-.004.284-.004.427");
}

.p5z2ihb8l {
  fill: var(--svg-color--706a4a, #706a4a);
  d: path("M36.866 36.905c.093.01.193-.028.275.048c-.094.003-.196.037-.275-.048");
}

.pbrh9obtg {
  fill: var(--svg-color--776826, #776826);
  d: path("M38.32 32.938v-.018l.264-.023c-.077.087-.169.057-.264.041");
}

.pmfpf1b3k {
  fill: var(--svg-color--69613a, #69613a);
  d: path("M27.924 27.08q-.072.023-.148.044c.029-.085-.068-.16-.014-.258c.121.022.09.159.162.214");
}

.pnb4dn_6r {
  fill: var(--svg-color--7f7545, #7f7545);
  d: path("m34.18 38.71l.114.059c-.046.089-.128.052-.196.062l-.122-.062c.053-.067.129-.062.204-.059");
}

.px-zfqs0j {
  fill: var(--svg-color--e9c001, #e9c001);
  d: path("M24.855 31.829c.195-.229.332-.212.534.063c.054.104.001.147-.091.171c-.123-.103-.271-.098-.418-.103c-.049-.036-.066-.077-.025-.131");
}

.q0qbyk_jx {
  fill: var(--svg-color--a2870b, #a2870b);
  d: path("M25.935 30.541c.135.132-.044.253-.013.381c-.108 0-.072-.067-.06-.126q.001-.087.005-.174c-.027-.067.007-.086.068-.081");
}

.q1juixquy {
  fill: var(--svg-color--786c37, #786c37);
  d: path("M25.908 30.18c.069-.005.137-.013.18-.078c.005.087.02.176-.057.256c-.088-.027-.049-.145-.123-.178");
}

.q75m7cbet {
  fill: var(--svg-color--28a2fe, #28a2fe);
  d: path("M28.334 34.18c-.082.057-.135.087-.209.063c.045-.076.096-.119.209-.063");
}

.q8-96abvf {
  fill: var(--svg-color--837639, #837639);
  d: path("M29.13 37.34c-.095.01-.164-.099-.266-.063c.007-.056.031-.111-.005-.166c.113.05.275.039.271.229");
}

.q89y039tv {
  fill: var(--svg-color--f3c801, #f3c801);
  d: path("M26.718 28.367c-.228-.137-.42-.327-.663-.445c-.077-.036-.192-.097-.046-.202a.13.13 0 0 1 .104-.034c.121.036.21.125.312.191c.048.035.104.057.153.089c.093.091.202.163.307.235c.005.079.028.161-.046.222c-.062.029-.085-.033-.121-.056");
}

.q8tzxzbnb {
  fill: var(--svg-color--95e469, #95e469);
  d: path("m31 30.808l-.006-.046h.649q0 .023.003.046z");
}

.qangk_bnj {
  fill: var(--svg-color--716320, #716320);
  d: path("M38.631 30.12c.113-.059.226-.104.324.023z");
}

.qbanncbgl {
  fill: var(--svg-color--30a1f5, #30a1f5);
  d: path("M28.16 33.691c.06.007.123 0 .163.057c.02.014.026.023.02.037l-.012.02q-.112-.026-.212-.053z");
}

.qjpv6wirl {
  fill: var(--svg-color--f0c600, #f0c600);
  d: path("m29.13 37.529l.006-.156c.281.091.158.238.057.385c-.078.049-.165.018-.247.024q-.042-.016-.043-.061c.079-.06.2-.069.227-.192");
}

.qk5cvhrht {
  fill: var(--svg-color--ccb02f, #ccb02f);
  d: path("M30.845 38.02c-.073-.033-.025.234-.155.061c-.023-.04-.075-.067-.063-.126c.078.001.185-.081.214.068z");
}

.qkvdppdih {
  fill: var(--svg-color--80733a, #80733a);
  d: path("M30.15 38.768q-.035.034-.071.072c-.044-.008-.094-.008-.112-.063c.066-.02.062-.064.039-.114a.21.21 0 0 1 .144.105");
}

.qmkftpk4n {
  fill: var(--svg-color--3d57b8, #3d57b8);
  d: path("M33.34 32.634c-.078-.053-.084-.145-.119-.221q.116-.006.23-.015c.007.099-.067.16-.111.236");
}

.qn8rdtwqv {
  fill: var(--svg-color--f8cc00, #f8cc00);
  d: path("M31.422 39.08v-.171c-.027-.056-.014-.126-.074-.167a.23.23 0 0 1-.076-.084a.9.9 0 0 1-.08-.344c.018-.063-.013-.128.016-.19c-.002-.063.014-.106.09-.094c.079.048.061.144.104.208l.076.249c.035.094.031.199.086.285c-.043.104.103.167.062.271c-.05.128-.125.098-.204.037");
}

.qnf0dhdwk {
  fill: var(--svg-color--665c2e, #665c2e);
  d: path("M25.756 32.2c.029-.047.062-.095.106-.164c.066.158.051.29.005.422c-.063-.069-.043-.175-.1-.248z");
}

.qo_dr2bwt {
  fill: var(--svg-color--f6cb00, #f6cb00);
  d: path("M32.589 24.562q-.025.026-.052.05c-.048.137-.004.277-.008.413c-.018.053-.009.108-.014.161c-.021.094-.098.188-.021.289v-.002c-.092.119-.156.117-.217-.011l.008-.153c.09-.089.073-.201.073-.312c0-.106.011-.212-.002-.315c-.021-.179.065-.215.216-.188q.054.023.017.068");
}

.qpp0m4luj {
  fill: var(--svg-color--7c7244, #7c7244);
  d: path("M34.736 38.613a.38.38 0 0 1-.248.095c.036-.106.129-.186.051-.294c-.035-.047-.058-.136.002-.16c.104-.041.082.085.121.13c.02.024.018.067.026.1c.013.042.056.075.048.129");
}

.qq4baabpl {
  fill: var(--svg-color--716632, #716632);
  d: path("m25.393 30.881l-.053-.063l-.018-.215c.104-.043.092.048.114.098c.007.066.019.131-.043.18");
}

.qrx1kzxgi {
  fill: var(--svg-color--6b612f, #6b612f);
  d: path("M31.26 24.782c.099.135.035.282.046.425q-.021.041-.038-.003a15 15 0 0 0-.008-.422");
}

.qvr4wjb2y {
  fill: var(--svg-color--786d39, #786d39);
  d: path("M28.04 26.866q.064.029.132.057c-.03.058-.089.124-.14.101c-.084-.034.019-.101.008-.158");
}

.qy-ci4bix {
  fill: var(--svg-color--7c6f34, #7c6f34);
  d: path("M36.874 27.02c.011.134.167.19.177.324l-.068.02c-.116-.068-.151-.253-.33-.234l.006.005c-.012-.198.128-.102.215-.115");
}

.r0y-r3tny {
  fill: var(--svg-color--776820, #776820);
  d: path("M25.482 33.971h.294q-.144.128-.294 0");
}

.r1ihm6buz {
  fill: var(--svg-color--645c35, #645c35);
  d: path("M34.36 25.535q.018.004.039.005a.1.1 0 0 1-.017.028l-.02-.037z");
}

.r26ca2bal {
  fill: var(--svg-color--797357, #797357);
  d: path("M37.888 35.889c-.091-.007-.196.029-.271-.057c.095 0 .192-.02.271.057");
}

.r2sns8-zn {
  fill: var(--svg-color--716427, #716427);
  d: path("M38.531 31.87c.307.104.61.113.923-.024c.034.092.005.188-.007.362c-.123-.197-.268-.154-.405-.163c-.194-.013-.404.048-.575-.105c.009-.036.03-.062.064-.07");
}

.r9d8c4-6s {
  fill: var(--svg-color--474229, #474229);
  d: path("M36.912 27.649v.133c-.049-.053-.137-.072-.122-.167z");
}

.ram6q8bpg {
  fill: var(--svg-color--172304, #172304);
  d: path("M34.723 33.435q.005-.032.014-.061c.16.036.331-.02.488.055q-.253.002-.502.006");
}

.rblh9ibhc {
  fill: var(--svg-color--5f5525, #5f5525);
  d: path("M26.1 28.429h.015c.006.004.011.016.009.021q-.016.032-.032-.003c-.004-.005.006-.011.008-.018");
}

.rd8e6ecpz {
  fill: var(--svg-color--00fefe, #00fefe);
  d: path("M35.27 32.413h-1.124c-.13.009-.135-.111-.185-.182c-.061-.087-.08-.212-.208-.24c-.116.069-.116.235-.246.294c-.065.02-.122-.006-.169-.049c-.074-.079-.112-.193-.232-.226a.65.65 0 0 1-.241-.24c-.021-.023-.028-.059-.06-.071c.033.02.041.056.066.08c.021.053.002.099-.025.145c-.119.169-.131.402-.313.534a.3.3 0 0 1-.214 0c-.142-.089-.196-.22-.202-.381c.072-.233.006-.472.034-.708c-.011-.033-.052.014-.02-.002c.034.185.007.371.017.557c-.021.164-.14.041-.204.069c-.174.11-.136.366-.323.465a.47.47 0 0 1-.269.016c-.137-.034-.175-.162-.237-.269c-.055-.089-.073-.203-.188-.246c-.053.006-.088.052-.133.073c-.128.064-.171.238-.335.253c-.11-.027-.133-.134-.188-.21c-.045-.063-.094-.145-.187-.049c-.094.162-.112.376-.324.451c-.286.012-.578.101-.849-.064q.566-.98 1.127-1.961c.148-.146.347-.173.533-.216c.429-.104.869-.146 1.309-.183c.09-.009.178-.004.251.059c.026.137.02.271.009.386c.032-.106-.011-.242.018-.37a.17.17 0 0 1 .163-.071c.436.067.896.03 1.312.221c.018.145.106.085.181.059a.42.42 0 0 1 .332.12z");
}

.rj7vbxb3e {
  fill: var(--svg-color--5d5322, #5d5322);
  d: path("m26.932 36.91l.115-.021c.008.054.079.092.035.162c-.08-.013-.113-.08-.15-.141");
}

.rj9d7be3k {
  fill: var(--svg-color--63ed9b, #63ed9b);
  d: path("m33.33 32.2l-.215-.208c.141-.004.21.071.215.208");
}

.rn978y6zc {
  fill: var(--svg-color--ebc202, #ebc202);
  d: path("M25.293 32.05c.059-.034.097-.082.097-.153c.14-.096.284-.188.424-.284c.087.022.106.059.035.124c-.104.182-.29.269-.459.375a.09.09 0 0 1-.104.004q-.024-.036.007-.066");
}

.rq_fhk1eq {
  fill: var(--svg-color--23adfe, #23adfe);
  d: path("M34.684 33.964c-.195.019-.192.213-.279.33c.007-.184.04-.345.279-.33");
}

.rrr7qsbpw {
  fill: var(--svg-color--6a6030, #6a6030);
  d: path("M37.3 28.05c-.043.053-.138.064-.117.159c-.051-.041-.111-.104-.07-.156c.022-.032.12-.004.187-.003");
}

.rwgrv-bzg {
  fill: var(--svg-color--746a3b, #746a3b);
  d: path("M30.84 38.03c-.051-.087-.142-.051-.214-.068a.1.1 0 0 1-.004-.046l-.002.004c.061.061.258-.15.22.11");
}

.rypo7sgde {
  fill: var(--svg-color--bb9b03, #bb9b03);
  d: path("M32.92 25.479c.052.02.1.045.093.112c-.063.041-.13-.004-.193-.014q.051-.046.1-.098");
}

.s100d1fby {
  fill: var(--svg-color--7b6d2f, #7b6d2f);
  d: path("M34.18 38.71c.017-.079-.005-.174.109-.231c.043.101.021.195.005.29q-.085.025-.114-.059");
}

.s13f27-xx {
  fill: var(--svg-color--967d0c, #967d0c);
  d: path("M33.827 37.866c-.044-.004-.087-.007-.107-.056c.077-.069.177-.045.266-.069c.036.069 0 .106-.056.132z");
}

.s3gjzdqok {
  fill: var(--svg-color--7e7032, #7e7032);
  d: path("M28.861 37.12c-.087-.018-.111.061-.159.102c.009-.065-.09-.134-.026-.18c.067-.05.137.016.185.078");
}

.s4nq-ub6a {
  fill: var(--svg-color--8d7b26, #8d7b26);
  d: path("M38.37 35.575q-.079-.055-.165-.11c.079.021.148-.104.217-.02c.03.036.009.102-.052.13");
}

.s71alqb9h {
  fill: var(--svg-color--71652c, #71652c);
  d: path("M30.37 38.818c.055-.008.124-.084.155.005c.031.094-.076.061-.117.084c-.07.034-.152.034-.217-.026c.041-.079.102-.092.179-.063");
}

.s78pxubju {
  fill: var(--svg-color--1fb6fe, #1fb6fe);
  d: path("M30.622 34.438h.392c-.131.073-.26.081-.392 0");
}

.s956sqbem {
  fill: var(--svg-color--f3c901, #f3c901);
  d: path("M34.463 37.683c.219.112.412.281.674.295c.115 0 .125.11.182.171c.002.146-.035.181-.147.12c-.22-.116-.435-.246-.651-.37c-.069-.032-.148-.044-.214-.088l.002.004c-.023-.054-.091-.093-.057-.167v.003c.076-.047.149-.032.211.032");
}

.sbg-f8bxq {
  fill: var(--svg-color--766e46, #766e46);
  d: path("m25.595 28.902l-.172-.116c.191-.163.096.105.172.116");
}

.sbh57nb2c {
  fill: var(--svg-color--ac9d00, #ac9d00);
  d: path("m33.985 33.12l.049-.056c.062.021.122.043.161.102c-.074-.002-.149.02-.21-.046m-.905 0l.046-.056c.061.02.123.041.161.102c-.073-.002-.15.02-.207-.046");
}

.se_dt1b3i {
  fill: var(--svg-color--1f2e49, #1f2e49);
  d: path("M29.1 33.383q.545 0 1.089.005q.03.009.021.021c-.004.014-.012.018-.012.018c-.369-.005-.736.043-1.098-.044");
}

.see_nbbkr {
  fill: var(--svg-color--6f6534, #6f6534);
  d: path("M38.575 31.398c.271-.074.539-.089.806.007q-.404-.002-.806-.007");
}

.sfqh83bbe {
  fill: var(--svg-color--73693a, #73693a);
  d: path("m30.37 38.818l-.179.063c-.043.005-.087.005-.11-.041q-.02-.094.071-.072c.077.009.157 0 .218.05");
}

.si_hjebbs {
  fill: var(--svg-color--5e552e, #5e552e);
  d: path("m35.11 37.705l-.02.041q-.01-.014-.024-.026z");
}

.skjo1pble {
  fill: var(--svg-color--9f8407, #9f8407);
  d: path("M31.384 38.713q-.116.004-.231.011l-.026.003l-.021-.012c.041-.061.104-.048.159-.052q.027-.007.053-.018c.022.022.041.045.066.068");
}

.sm6gf44xn {
  fill: var(--svg-color--f9cd00, #f9cd00);
  d: path("M37.833 28.3q.002-.026.002-.056c.126-.069.236-.177.396-.174c.088.096.071.174-.037.236l-.044.036c-.064.085-.143.021-.214.019z");
}

.sn56qrs6s {
  fill: var(--svg-color--f3f3f2, #f3f3f2);
  d: path("m37.3 36.15l-.097-.161c.005-.063.061-.045.094-.058l.107.01c.104.051.118.117.045.206c-.05.05-.097.054-.149.003");
}

.spfudib2s {
  fill: var(--svg-color--776e3e, #776e3e);
  d: path("M35.85 26.807c.024-.12-.032-.25.041-.364c-.049.119.127.262-.041.364");
}

.sqiy7ebay {
  fill: var(--svg-color--76661c, #76661c);
  d: path("m38.1 27.679l-.13-.067c.01-.046-.048-.133.005-.13c.097.003.13.098.125.197");
}

.sr7ufkbjw {
  fill: var(--svg-color--7e7650, #7e7650);
  d: path("M27.463 26.1c.021.075.141.092.117.193c-.061-.085-.147-.067-.241-.033c-.003-.117.067-.133.124-.16");
}

.ssmsarbcn {
  fill: var(--svg-color--5d573c, #5d573c);
  d: path("M36.93 37.29q-.062-.055-.121-.111c.067.04.152-.061.205.029c.005.006-.053.053-.084.082");
}

.suwnyq7ix {
  fill: var(--svg-color--7f7962, #7f7962);
  d: path("m32.22 38.38l-.002.361c-.089-.12-.062-.24.002-.361");
}

.svzfct59i {
  fill: var(--svg-color--6f6740, #6f6740);
  d: path("M32.55 39.1c.072-.014.156.015.205-.064c.04-.018.079.045.118 0l.05.064a.37.37 0 0 1-.373 0");
}

.swl7yd87j {
  fill: var(--svg-color--80784e, #80784e);
  d: path("m35.1 25.524l.06.119c-.002.057-.03.13-.084.089c-.074-.058-.03-.142.024-.208");
}

.sxzp-s3wb {
  fill: var(--svg-color--675a20, #675a20);
  d: path("m38.746 32.88l-.171.018c-.006-.16.035-.31.081-.458c0-.005.012-.005.016-.003l.021.02a.34.34 0 0 1 .062.188a1.3 1.3 0 0 1-.009.235");
}

.szff83bpz {
  fill: var(--svg-color--eec401, #eec401);
  d: path("M28.804 37.659c.021.047.069.051.109.063v.02c-.085.058-.05.118 0 .177c.011.091-.024.191.053.269c-.006.057.029.126-.052.157l-.105-.212c-.015-.09.029-.191-.055-.268c.016-.07-.032-.155.05-.206");
}

.t_ua8_60e {
  fill: var(--svg-color--807c66, #807c66);
  d: path("M32.498 25.319q-.007-.05-.012-.103l.012-.162h.057c-.022.091 0 .184-.057.265");
}

.t-vo-nbbq {
  fill: var(--svg-color--615728, #615728);
  d: path("M38.52 35.03a.1.1 0 0 0-.035.005c0-.056-.093-.115-.035-.151c.072-.044.111.03.122.101z");
}

.t00h-1r_v {
  fill: var(--svg-color--192633, #192633);
  d: path("m35.568 33.435l-.056-.111c.082.007.154.029.209.094c-.047.043-.1.027-.153.017");
}

.t1ubx3lef {
  fill: var(--svg-color--534c30, #534c30);
  d: path("M28.999 26.28c-.018-.12.023-.21.151-.308c-.008.154-.056.241-.151.308");
}

.t698ne93g {
  fill: var(--svg-color--fbfa02, #fbfa02);
  d: path("M30.62 29.473c0-.089.082-.135.11-.209c.28-.202.617-.14.928-.177c.488-.059.977.027 1.464.059a.7.7 0 0 1 .324.118c.06.063.151.118.057.224c-.096.089-.214.075-.327.059c-.229-.037-.462-.028-.691-.041a9.4 9.4 0 0 0-1.568.048c-.106.009-.215.009-.297-.081");
}

.t8olxk_5t {
  fill: var(--svg-color--63ed9b, #63ed9b);
  d: path("M32.11 27.891c-.019.136.046.281-.042.409c.015-.137-.062-.284.042-.409");
}

.ta525sf7k {
  fill: var(--svg-color--9b851d, #9b851d);
  d: path("M35.31 37.436c-.118-.082-.15-.159-.024-.281c.068.097.051.182.024.281");
}

.tci3nzbmp {
  fill: var(--svg-color--4363fe, #4363fe);
  d: path("M28.16 33.691q.087-.166.171-.332c.109-.01.208-.059.322-.053c.164 0 .328-.018.492.017c.349.067.703.019 1.056.033h2.704c.321.003.643 0 .962 0c.281.003.563 0 .844 0c.157 0 .313.003.47 0c.115-.015.223.034.336.024h.061s-.041-.003-.075-.003c-.228.013-.364-.178-.552-.25c-.265-.122-.549-.215-.736-.455c-.069-.089-.185-.195-.016-.307c.357-.038.717-.094 1.064.047q.6 1.018 1.197 2.037c.062.102.035.146-.082.143c-.046-.003-.092 0-.135 0h-8.302c-.313 0-.314-.003-.159-.269c.11-.193.226-.382.337-.572c.077-.056.148-.006.217.024c.087.009.176 0 .265.005c-.092-.005-.183.006-.271-.01c-.048-.042-.124-.028-.17-.079");
}

.tdgna6buo {
  fill: var(--svg-color--6e6330, #6e6330);
  d: path("M34.838 26.01q.055.047.108.098c.005.039.011.107-.034.095c-.094-.027-.073-.12-.074-.193");
}

.tf0n1cclr {
  fill: var(--svg-color--94e46a, #94e46a);
  d: path("M32.16 32.08c-.042-.02-.043-.058-.045-.098v-.68h.045z");
}

.tfmqpt0ta {
  fill: var(--svg-color--94e26c, #94e26c);
  d: path("M32.12 30.14h.057v.42h-.057z");
}

.tj_wsv6uj {
  fill: var(--svg-color--827536, #827536);
  d: path("m25.935 30.541l-.067.081c-.048-.048-.095-.099-.166-.174c.115 0 .216-.064.233.093");
}

.tj897wbez {
  fill: var(--svg-color--25a8fe, #25a8fe);
  d: path("M31.795 33.547c.167.003.34-.023.504.051c-.168.041-.335.099-.501-.007q-.028-.014-.021-.029q.009-.015.018-.015");
}

.tjojx0bvt {
  fill: var(--svg-color--1eb9fe, #1eb9fe);
  d: path("M36.16 34.15c-.079.116-.146.093-.232 0z");
}

.tk3mlm3hc {
  fill: var(--svg-color--756d46, #756d46);
  d: path("m25.756 31.25l.118-.117q.002.069-.002.13c-.005.05.007.125-.065.119c-.063-.006-.042-.084-.051-.132");
}

.toode_bbt {
  fill: var(--svg-color--62ed9c, #62ed9c);
  d: path("M31.508 31.346a.5.5 0 0 1 .276-.268c-.064.137-.14.193-.276.268m-.388.325a.3.3 0 0 1 .222-.201a.34.34 0 0 1-.222.201");
}

.tqipfrbha {
  fill: var(--svg-color--615931, #615931);
  d: path("M34.47 38.08v-.06l-.007.004a.3.3 0 0 1 .041.044q-.018.002-.041.008z");
}

.tqiy4qbfs {
  fill: var(--svg-color--edebde, #edebde);
  d: path("M32.814 24.51a.2.2 0 0 0-.016-.041c.096-.009.195-.037.28.041z");
}

.tyh2njbrh {
  fill: var(--svg-color--918653, #918653);
  d: path("M31.4 38.23c-.07-.05-.084-.13-.104-.208c.142.019.068.139.104.208");
}

.tzc3kkb_o {
  fill: var(--svg-color--786e3c, #786e3c);
  d: path("M36.697 37.34q.065.022.13.05c-.035.049-.068.123-.137.088c-.067-.035.013-.09.007-.138");
}

.u0eevxm5o {
  fill: var(--svg-color--9a810f, #9a810f);
  d: path("M32.34 25.05q.023-.003.041-.008c-.013.095.068.22-.092.266c.019-.087.033-.174.051-.258");
}

.u5aon3lel {
  fill: var(--svg-color--f5ca01, #f5ca01);
  d: path("M35.749 25.467c.079.051.134.089.055.205c-.13.188-.226.402-.337.604c-.069.031-.069.192-.202.109h.003c-.097-.061-.062-.119.002-.179l.358-.624c.06-.019.022-.14.121-.115");
}

.u6y11hr8k {
  fill: var(--svg-color--797253, #797253);
  d: path("M37.618 36.638c-.036.065-.027.173-.146.164q-.045.036-.077-.01c.064-.058.071-.128.051-.204a.1.1 0 0 1 .063-.034c.052.008.093.027.109.084");
}

.ua9oanbqj {
  fill: var(--svg-color--635a31, #635a31);
  d: path("m35.11 37.705l.016-.043q.013.016.025.024q-.02.011-.041.019");
}

.uci9k5-1o {
  fill: var(--svg-color--72693b, #72693b);
  d: path("M31.535 25.522c-.02-.039-.034-.075-.053-.112c.14.047.282-.009.422.014c-.029.173-.171.086-.266.111c-.033-.013-.074.028-.103-.013");
}

.ufi795cxs {
  fill: var(--svg-color--97e367, #97e367);
  d: path("M30.07 30.735a.9.9 0 0 1 .395-.004a.7.7 0 0 1-.395.004");
}

.uhy9wx5zp {
  fill: var(--svg-color--19c4fe, #19c4fe);
  d: path("M32.12 34.33c-.128-.021-.256-.045-.411-.071a.5.5 0 0 1 .411.03q.027.016.018.029a.02.02 0 0 1-.018.012");
}

.ujs2_ub1y {
  fill: var(--svg-color--213300, #213300);
  d: path("M31.957 33.33c.251.053.5.106.749-.002c.08-.063.145-.02.21.028q.024.032.008.071l-1.822-.002c0-.014 0-.023-.002-.036c.286-.051.58.063.859-.062z");
}

.ukuy2ybem {
  fill: var(--svg-color--898471, #898471);
  d: path("M25.776 32.422q-.434-.004-.869-.005l-.011-.045a.14.14 0 0 1 .069-.052c.19-.021.378-.005.568-.009c.073.004.149-.012.219.03q.037.032.024.081");
}

.urb9mhcnw {
  fill: var(--svg-color--7b7147, #7b7147);
  d: path("M25.652 31.05c-.082-.043-.195.024-.263-.077c.093.012.205-.041.263.077");
}

.usou6ib7g {
  fill: var(--svg-color--f8f8f7, #f8f8f7);
  d: path("M26.19 27.619q.059-.048.112-.1c.078-.084.143-.029.208.021l.016.017a.27.27 0 0 1 .022.205c.012.111-.045.164-.15.173l-.262-.201q.028-.057.054-.115");
}

.uvhf2ub6f {
  fill: var(--svg-color--94822d, #94822d);
  d: path("M36.697 36.534c.07-.007.057.092.121.097l.031.009l-.031.073l-.148-.015z");
}

.ux5h8gbnw {
  fill: var(--svg-color--716944, #716944);
  d: path("M35.27 26.21c-.012.06-.045.118-.002.179c-.09-.006-.154-.047-.214-.143c.081-.014.147-.026.216-.036");
}

.v-49kgb1k {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v3h64v-3c0-6.075-3.373-11-10-11M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-3H0z");
}

.v3ftc1b1v {
  fill: var(--svg-color--6d653d, #6d653d);
  d: path("M33.971 38.22c-.005-.053.004-.099.07-.105a.3.3 0 0 1 .057.192c.003.046.068.104.008.135c-.073.034-.092-.057-.133-.091c-.002-.044-.026-.087-.002-.131");
}

.v3wt20fyk {
  fill: var(--svg-color--7e702f, #7e702f);
  d: path("M34.37 25.958c-.128-.038-.23-.055-.29-.156c.195-.128.195-.128.29.156");
}

.v6tbxjplv {
  fill: var(--svg-color--3e5bd6, #3e5bd6);
  d: path("M31.463 32.666c-.068-.073-.14-.147-.161-.253l.334-.013c-.023.113-.072.207-.173.266");
}

.v7q-qmoin {
  fill: var(--svg-color--86772c, #86772c);
  d: path("M27.785 37.604c.106-.008.194-.044.264.023c.027.031-.002.07-.034.082c-.091.034-.163.006-.23-.105");
}

.v85b83bxw {
  fill: var(--svg-color--7b734e, #7b734e);
  d: path("M25.06 31.09c.094.008.197-.033.273.054c-.092-.006-.194.03-.273-.054");
}

.v99pg2aml {
  fill: var(--svg-color--e6be02, #e6be02);
  d: path("M36.654 36.736q0-.023.016-.038c.055-.048.105-.061.148.015l.002.012c.087.108.227-.005.321.07l-.008-.002c.052.083.212-.045.22.117c-.056.087-.143.032-.212.043c-.084-.058-.188.01-.275-.048l.006.003c-.065-.065-.162-.003-.229-.057a.1.1 0 0 1 .011-.115");
}

.vbwld6bhk {
  fill: var(--svg-color--3d57b8, #3d57b8);
  d: path("M32.434 32.634c-.075-.053-.084-.145-.116-.221a.4.4 0 0 0 .228-.018c.009.102-.069.163-.112.239");
}

.vc18zkcna {
  fill: var(--svg-color--847d5f, #847d5f);
  d: path("M37.518 28.782c.043.004.079-.007.105-.046c.036.056.077.128-.007.158c-.066.025-.085-.059-.098-.112");
}

.vdr_oabau {
  fill: var(--svg-color--49f1b5, #49f1b5);
  d: path("M31 30.808c-.136.015-.271.024-.397-.048c.13-.059.26-.084.392.002q.024.012.019.029q-.008.016-.014.017");
}

.vg5f9fbqi {
  fill: var(--svg-color--70642c, #70642c);
  d: path("m25 30.495l-.09-.001c-.038-.256.154-.132.256-.156c.053.166-.148.065-.166.157");
}

.vlgrpbysy {
  fill: var(--svg-color--01fefd, #01fefd);
  d: path("m31.04 28.725l1.045-1.852c.347.656.747 1.229 1.038 1.865c-.324-.034-.636-.127-.951-.192c-.096-.118-.051-.256-.046-.383c-.023.063-.005.123-.011.181c-.003.07.004.14-.045.193c-.342.065-.677.182-1.03.188");
}

.vm7eq4bqb {
  fill: var(--svg-color--6e674a, #6e674a);
  d: path("M39.38 31.405c.086-.072.082-.146 0-.219l.002-.026c0-.037.021-.089.045-.075c.126.061.045.179.058.27c.007.052.033.139-.05.152c-.047.009-.053-.058-.055-.102");
}

.vq4blbgoo {
  fill: var(--svg-color--887c47, #887c47);
  d: path("M36.945 27.83c.082.008.085-.083.138-.11c.01.069.034.149-.048.184c-.049.021-.074-.031-.09-.074");
}

.vs-2aacwz {
  fill: var(--svg-color--6b6133, #6b6133);
  d: path("m26.14 35.3l.155-.006c-.021.095-.105.149-.157.223q0-.11.002-.217");
}

.vv17s-ble {
  fill: var(--svg-color--27a4fe, #27a4fe);
  d: path("M29.26 33.728c.095-.12.171-.067.272 0a.36.36 0 0 1-.272 0");
}

.vw89uc0cj {
  fill: var(--svg-color--8b804d, #8b804d);
  d: path("M34.924 25.686c-.093-.079-.095-.18-.082-.286c.076.079.07.185.082.286");
}

.w-w45ubqe {
  fill: var(--svg-color--655c2f, #655c2f);
  d: path("m28.18 37.23l-.151-.061l-.018-.059l-.005.004l.183-.002c.041-.002.111-.049.109.039c-.002.054-.062.077-.118.079");
}

.w0q5m4xst {
  fill: var(--svg-color--786c39, #786c39);
  d: path("M37.4 36.424c-.051-.077-.162-.1-.171-.21a.11.11 0 0 1 .06-.074a.6.6 0 0 1 .195-.005c.031.019.053.041.026.079c-.028.067-.089.125-.049.207q-.029.028-.061.003");
}

.w3mew4b-l {
  fill: var(--svg-color--6c6336, #6c6336);
  d: path("M24.967 32.2q-.03.007-.057.009q-.03.027-.064.007c-.031-.05 0-.115-.036-.167c-.007-.075-.03-.155.046-.216c.004.047 0 .097.057.118a.24.24 0 0 1 .054.249");
}

.w7a-bublj {
  fill: var(--svg-color--6e6950, #6e6950);
  d: path("M38.843 30.875q.004-.06.003-.115c.047.043.055.102.055.159c0 .036.017.096-.051.081c-.022-.004-.041-.045-.061-.071c.002-.034.035-.037.054-.054");
}

.w8vnhsfuc {
  fill: var(--svg-color--ecc302, #ecc302);
  d: path("M35.758 26.29c.098-.272.266-.388.525-.356c.052.071-.002.096-.053.121c-.123.125-.283.212-.34.392c-.035.119.031.251-.041.364c-.087-.031-.114-.094-.101-.179c-.026-.114-.057-.229.01-.342");
}

.wazusbbjv {
  fill: var(--svg-color--70642d, #70642d);
  d: path("M25.548 29.387q-.134-.007-.269-.017c.094-.07.185-.099.269.017");
}

.wc7pcdbvw {
  fill: var(--svg-color--6f684c, #6f684c);
  d: path("M33.987 37.927c.065-.048.061-.112.047-.181l.063.02l-.006-.005q.009.078.015.157c-.033.101-.074.074-.119.009");
}

.weeb7rb5y {
  fill: var(--svg-color--f6cb00, #f6cb00);
  d: path("M29.29 38.4c.104-.24.203-.48.309-.718c.024-.058-.015-.189.135-.108c.09.047.115.092.072.184c-.104.21-.202.422-.304.634c-.06.05.036.245-.158.164h.004c-.051-.041-.117-.076-.058-.156");
}

.wenhe9bpv {
  fill: var(--svg-color--8e7c27, #8e7c27);
  d: path("M28.709 25.436c-.066.113-.176.018-.258.048c-.066.029-.082-.004-.071-.06c.098-.092.214-.053.325-.046c.01.017.015.036.004.058");
}

.wepy6vz-b {
  fill: var(--svg-color--22affe, #22affe);
  d: path("M34.33 33.682c-.085.02-.171.039-.287.064c.092-.11.176-.126.287-.064");
}

.wl-mlkhur {
  fill: var(--svg-color--f1c700, #f1c700);
  d: path("M37.518 28.782c-.135-.241.076-.397.14-.589c.06-.021.032-.13.123-.115a.15.15 0 0 1 .089.156a.12.12 0 0 1-.036.066c-.119.124-.123.299-.21.436c-.006.087-.047.091-.106.046");
}

.wolu6dbdj {
  fill: var(--svg-color--19260a, #19260a);
  d: path("m30.2 33.426l-.007-.038h.908c.002.013.002.022.002.036z");
}

.wumaxgi2p {
  fill: var(--svg-color--686245, #686245);
  d: path("m25.6 35.09l.112.047c.007.04.048.108-.009.108c-.084 0-.092-.089-.103-.155");
}

.wumkggtxl {
  fill: var(--svg-color--716b50, #716b50);
  d: path("M33.509 38.647c.106.067-.013.236.128.288c-.057.054-.129.085-.184.034c-.058-.045.043-.073.05-.117c.008-.066.005-.135.006-.205");
}

.x-lytkb-f {
  fill: var(--svg-color--1bbefe, #1bbefe);
  d: path("M29.951 33.534c-.128.024-.21.037-.351.061c.129-.103.209-.13.351-.061");
}

.x1p7g9mtu {
  fill: var(--svg-color--f6cb00, #f6cb00);
  d: path("M33.559 37.925c.024.08-.05.161.004.238c.053.132.076.272.104.414c.096.06.015.191.102.257l.008.025l-.14.076c-.095.041-.1-.025-.104-.086c-.005-.067.014-.137-.024-.202v-.013c-.07-.084.034-.219-.084-.288l-.028-.19c-.005-.087-.068-.145-.104-.218q.105-.014.212-.026c.019-.015.04-.009.055.013");
}

.x2wwb4_xx {
  fill: var(--svg-color--706845, #706845);
  d: path("M37.821 36.06c.079-.026.128.038.194.052c-.141.263-.119-.07-.194-.052");
}

.x3699jbel {
  fill: var(--svg-color--827746, #827746);
  d: path("M38.525 32.361c-.07.002-.139.006-.199.056c-.05-.095-.002-.186-.017-.289c.13.01.147.123.219.174c.011.017.014.026.011.04q-.007.019-.014.019");
}

.x4clsw5cj {
  fill: var(--svg-color--595024, #595024);
  d: path("m28.709 25.436l-.004-.058l.037.013z");
}

.x567okbom {
  fill: var(--svg-color--71683c, #71683c);
  d: path("m29.82 38.12l-.003.453a.44.44 0 0 1 .003-.453");
}

.x57a214ao {
  fill: var(--svg-color--6f694b, #6f694b);
  d: path("m38.85 30.765l-.285-.003q.082-.033.16-.074c.09-.051.088-.053.125.077");
}

.x9u-gcbqb {
  fill: var(--svg-color--766d45, #766d45);
  d: path("M25.862 30.796c.01.048.007.1.06.126c-.004.076.032.16-.05.219c-.007-.048-.013-.095-.061-.121c.008-.077-.012-.159.051-.224");
}

.xa96a2xlo {
  fill: var(--svg-color--e1e0dc, #e1e0dc);
  d: path("M31.26 38.663c-.051-.081-.232.02-.215-.156l.002-.058c.069-.046.067-.195.205-.144l.061.34q-.014.041-.053.018");
}

.xc6cifb4y {
  fill: var(--svg-color--665d34, #665d34);
  d: path("m28.973 38.18l.117.251c-.091.019-.138-.024-.184-.073v-.033a.2.2 0 0 1 .039-.125z");
}

.xd4-_3q0x {
  fill: var(--svg-color--e0b901, #e0b901);
  d: path("M38.571 34.985c.052.07.103.138.022.22c-.12.011-.086-.08-.096-.143c.006-.045.013-.086.074-.077");
}

.xf_wiachn {
  fill: var(--svg-color--837018, #837018);
  d: path("M24.81 32.05c.055.043.043.109.05.165a.25.25 0 0 1 .053.159c-.005.018-.005.031-.005.048c-.055.048-.109.087-.109-.03c-.003-.115.006-.227.011-.342");
}

.xj-euxbko {
  fill: var(--svg-color--fccf00, #fccf00);
  d: path("M26.976 27.833c-.068-.065-.16-.063-.247-.065q-.069-.073-.006-.149q.133-.004.267-.003c.159.102.196.229.075.386c-.085-.027-.007-.141-.089-.169");
}

.xkqez-bri {
  fill: var(--svg-color--20b4fe, #20b4fe);
  d: path("M28.963 34.478c-.195-.065-.394-.011-.583-.056c.203-.037.405-.064.583.056");
}

.xl4aeibwy {
  fill: var(--svg-color--53491e, #53491e);
  d: path("M26.876 26.876q-.05-.031-.095-.062c.002-.063.037-.136.093-.107c.074.032-.013.109.002.169");
}

.xm3s8hb-x {
  fill: var(--svg-color--6c6231, #6c6231);
  d: path("M27.418 36.31c-.031-.032-.066-.065-.096-.1c.023-.091.093-.052.151-.05c-.007.053.037.128-.055.15");
}

.xmlg_vbri {
  fill: var(--svg-color--20b3fe, #20b3fe);
  d: path("M34.2 33.99c.021.115-.016.188-.164.258z");
}

.xqml7b_ww {
  fill: var(--svg-color--98821e, #98821e);
  d: path("M35.21 25.428c-.054-.091 0-.217-.108-.291c.094-.075.146.024.215.031c.043.052.048.102-.002.151c-.032.041-.039.104-.107.104z");
}

.xqvvy442h {
  fill: var(--svg-color--83742d, #83742d);
  d: path("m29.29 38.4l.058.155c-.095.012-.171-.046-.181-.121c-.01-.06.082-.014.123-.034");
}

.xuhvcjbpb {
  fill: var(--svg-color--22affe, #22affe);
  d: path("M30.03 33.721h.265c-.084.094-.149.105-.265 0");
}

.xv7-sebxa {
  fill: var(--svg-color--f3c801, #f3c801);
  d: path("M27.14 35.566c-.076.221-.149.44-.266.645c-.018.114-.024.241-.187.246c-.041-.008-.07-.028-.075-.072c.103-.291.21-.58.313-.87c.102-.111.167-.064.215.051");
}

.xvfqkxfun {
  fill: var(--svg-color--f0f0ef, #f0f0ef);
  d: path("M24.967 32.2c-.086-.066-.055-.16-.055-.249c.159-.097.305-.136.381.098v.057c-.066.181-.224.043-.326.094");
}

.xy70yxbvt {
  fill: var(--svg-color--7c713f, #7c713f);
  d: path("m38.26 29.372l.161.012v.039c-.056.06-.099.14-.189.159q.011-.106.028-.21");
}

.xyn_s5b4s {
  fill: var(--svg-color--c4a927, #c4a927);
  d: path("M24.91 32.363c.214-.084.428-.069.644-.004q-.322 0-.644.004");
}

.y-nrx8t0b {
  fill: var(--svg-color--716427, #716427);
  d: path("m26.02 35.607l-.051.186c-.071-.087-.185-.184.051-.186");
}

.y-w_9vbhv {
  fill: var(--svg-color--706638, #706638);
  d: path("m32.912 38.14l-.403-.021c.185-.146.399-.061.593-.116c.024-.007.064.129-.01.192c-.061-.014-.112-.07-.18-.055");
}

.y1z9oabpi {
  fill: var(--svg-color--face00, #face00);
  d: path("m38.575 31.398l-.095.063c-.057-.053-.048-.106-.005-.162l.1-.062c.263-.066.541.031.806-.051h-.004q.184.11 0 .219h.004a2.6 2.6 0 0 0-.806-.007");
}

.y32ampb5k {
  fill: var(--svg-color--7d713c, #7d713c);
  d: path("m28.38 25.424l.071.06c-.066.041-.143.16-.206.072c-.056-.079.055-.12.135-.132");
}

.y7ici8ben {
  fill: var(--svg-color--16cbfe, #16cbfe);
  d: path("M33.612 33.593c.077-.091.171-.053.267.002h-.267z");
}

.ybo2ns_xg {
  fill: var(--svg-color--655d3a, #655d3a);
  d: path("M31.535 25.522c.034.002.075-.046.104.013c-.123.089-.266.028-.397.05c-.028.005-.08.005-.06-.048c.014-.024.055-.041.082-.061q.024-.042.049 0c.058.089.145.046.222.046");
}

.yc0dyqzpl {
  fill: var(--svg-color--89792d, #89792d);
  d: path("M37.25 26.96q-.03-.047-.06-.089c.087-.041.171-.128.262-.012c-.091-.014-.148.039-.202.101");
}

.yfo-mpbcv {
  fill: var(--svg-color--685f3a, #685f3a);
  d: path("m26.718 28.367l.12.056a.19.19 0 0 1-.096.133c-.056-.058-.004-.131-.024-.189");
}

.yi2wtcceh {
  fill: var(--svg-color--776c39, #776c39);
  d: path("m28.913 37.741l.274.017c-.046.124-.264-.045-.264.156l-.043.013c-.083-.077-.091-.143.033-.186");
}

.yi3qbga1c {
  fill: var(--svg-color--71693e, #71693e);
  d: path("M36.447 36.32c.018.085.133.018.156.095l-.267.007c.001-.074.032-.117.111-.102");
}

.yignl5buv {
  fill: var(--svg-color--9e840a, #9e840a);
  d: path("m37.19 27.03l-.264-.003c.004-.195.204-.058.266-.152c.041.015.064.043.06.089z");
}

.yl4m4-7ep {
  fill: var(--svg-color--888473, #888473);
  d: path("m31.27 25.2l.038.003q0 .137.003.27h-.048c0-.09.005-.181.007-.273");
}

.ymkoa6brj {
  fill: var(--svg-color--947e13, #947e13);
  d: path("M36.66 36.848q-.031.026-.063.056c-.108-.002-.155-.077-.198-.159c.084.017.174.118.256-.008z");
}

.yr49opzwo {
  fill: var(--svg-color--8d7915, #8d7915);
  d: path("M36.06 36.684v-.031l.051-.028c.074.065.172.117.168.236c-.08-.05-.119-.153-.219-.177");
}

.ytg0e6bga {
  fill: var(--svg-color--f1c701, #f1c701);
  d: path("M37.411 35.1c.063-.065.084-.125.2-.013c.164.16.393.256.591.379c.04.063.187-.041.165.11c-.069.128-.125.166-.266.041c-.176-.154-.395-.255-.595-.381c-.057-.028-.18-.008-.095-.136");
}

.yudtzbciv {
  fill: var(--svg-color--fed100, #fed100);
  d: path("M27.16 34.803c1.639-2.824 3.265-5.628 4.917-8.471l4.917 8.471z");
}

.yw4x6vbgs {
  fill: var(--svg-color--7b6f39, #7b6f39);
  d: path("m28.694 37.544l.112.108l.004.033a.26.26 0 0 1-.031.162l-.026.021c-.069-.01-.003-.217-.154-.106c-.009-.093.044-.156.095-.218");
}

.yw82gtb5e {
  fill: var(--svg-color--6c6546, #6c6546);
  d: path("M36.552 27.09c-.044.058-.153.021-.174.118c-.063-.054-.123-.108.025-.116c.049-.005.098-.002.149-.002");
}

.yx3b6lbgi {
  fill: var(--svg-color--7f7234, #7f7234);
  d: path("M27.05 27.981c.123-.146.029-.255-.058-.366c.26.085.188.254.106.425c-.05.012-.07-.005-.048-.059");
}

.yz8lgob8x {
  fill: var(--svg-color--5f5630, #5f5630);
  d: path("M26.344 36.27q.01-.105.016-.21l.053.054c.005.04.005.083.014.12c.007.029.039.06-.005.079c-.035.012-.063-.009-.078-.043");
}

.z_tv3gb5e {
  fill: var(--svg-color--796b2c, #796b2c);
  d: path("M31.26 38.31c-.097.007-.084.169-.205.144c-.015-.142.08-.232.156-.329c.027.059.064.116.049.185");
}

.z-6xz4khx {
  fill: var(--svg-color--857b4b, #857b4b);
  d: path("m37.5 36.583l-.055.005c-.063-.041-.056-.102-.041-.164l.062-.003q.047.055.098.108c-.008.034-.042.039-.064.054");
}

.z06g8hrrz {
  fill: var(--svg-color--90823e, #90823e);
  d: path("M35.27 26.386c.097.018.12-.102.202-.109c-.019.124-.012.293-.202.109");
}

.z077yybii {
  fill: var(--svg-color--1dbbfe, #1dbbfe);
  d: path("M35.12 34.26c-.109.028-.181-.027-.274-.105c.131-.018.197.064.274.105");
}

.z4ey4jb6v {
  fill: var(--svg-color--6ca401, #6ca401);
  d: path("M33.494 32.26c.098-.11.094-.286.239-.359c.087.126.114.276.167.415c.197.496.61.671 1.087.76c.19.052.306.262.525.25c.041.026.12.033.056.111q-.17-.004-.344-.006c-.148-.048-.301-.012-.449-.024c-.144-.017-.265-.104-.409-.119a.5.5 0 0 1-.176-.068a.8.8 0 0 0-.199-.096c-.249-.123-.536-.188-.678-.468c-.008-.094.055-.162.08-.244a.5.5 0 0 1 .101-.152");
}

.z5d3xv9dg {
  fill: var(--svg-color--9d8411, #9d8411);
  d: path("M29.453 25.15c.023.021.051.045.073.067c.033.114.058.229.062.35a.2.2 0 0 1-.025.074c-.057.114-.055.237-.051.359q-.043.038-.082-.002c-.018-.238-.004-.479-.008-.715c.002-.046-.01-.095.031-.133");
}

.z5don_s7u {
  fill: var(--svg-color--a48b16, #a48b16);
  d: path("M25.293 32.1q.046 0 .097.005c.082.186.249.043.366.092l.018.041a.11.11 0 0 1-.062.065c-.273.021-.545.094-.805-.052q-.02-.046.019-.076c.115-.058.242-.052.367-.075");
}

.za_-5y_wc {
  fill: var(--svg-color--eec503, #eec503);
  d: path("M37.13 35.744c.056.061.128.029.195.034c.089.064.2-.003.292.056l-.005-.002c.08.071.19-.006.271.057l-.005-.002c.051.082.203-.046.219.108l-.086.114c-.082.052-.126-.043-.194-.052a4 4 0 0 0-.191-.005a1 1 0 0 0-.235-.05a.4.4 0 0 1-.104-.021c-.101-.048-.207-.079-.296-.148a.07.07 0 0 1-.023-.045c.024-.125.086-.106.162-.044");
}

.zj9qhsbvg {
  fill: var(--svg-color--6b6236, #6b6236);
  d: path("M35.749 25.467c-.063.013-.039.123-.121.116c.063-.063-.098-.145.011-.195c.049-.022.09.031.11.079");
}

.zk16wvbrd {
  fill: var(--svg-color--786f46, #786f46);
  d: path("M30.845 38.02c-.019.075.036.198-.095.205c-.084.007-.059-.087-.061-.145c.056-.004.082-.091.156-.06");
}

.zm8r0kqej {
  fill: var(--svg-color--7d6f2d, #7d6f2d);
  d: path("M35.05 37.572c-.101-.061-.217-.112-.211-.132c.032-.117.155-.119.257-.164c.047.109-.054.174-.046.296");
}

.zovbtd9xr {
  fill: var(--svg-color--807334, #807334);
  d: path("m26.14 27.734l-.13-.015q.058-.083.118-.165c.051-.025.072.009.089.047a.13.13 0 0 1-.077.133");
}

.zsm_40bkf {
  fill: var(--svg-color--25a7fe, #25a7fe);
  d: path("M35.489 33.735c-.169.105-.343.217-.436-.133c.142.148.279.194.436.133");
}

.zuwefd0yd {
  fill: var(--svg-color--675d2d, #675d2d);
  d: path("m38.686 32.666l.007-.21c.063.041.162-.021.212.067q-.03.03-.059.063c-.032.043-.059.097-.114.117q-.039-.001-.046-.037");
}

.zwz361bjz {
  fill: var(--svg-color--7a6e33, #7a6e33);
  d: path("m27.05 27.981l.049.059c-.029.082-.038.188-.171.161c.025-.12.103-.235.051-.368c.095.017.064.092.071.148");
}

.zz5f71b5i {
  fill: var(--svg-color--f8ba01, #f8ba01);
  d: path("M32.823 31.899c.146-.036.169.087.217.171q.094.17.183.343c.091.048.101.137.119.221c.176.233.441.318.692.429q.029.075-.049.056c-.692-.126-1.162-.62-1.162-1.22");
}

</style>
