<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pwzksgbti"/><path class="hr7cw47jv"/><path class="tqyba-tll"/><path class="ztrngybee"/><g class="d2kvgvbvc"><path class="wwu7mrbnt"/><path class="il0tzxo5v"/><path class="tjis19bmo"/><path class="ms3toqbgr"/><path class="f_mei872j"/><path class="j91zh3b7l"/><path class="dt1ql-k8c"/><path class="q576ofbvc"/><path class="za_dgvb9q"/><path class="ovpzd3x_p"/><path class="sz04ebcjf"/><path class="hgpfamceb"/><path class="xfov0_bzr"/><path class="n_cb1iblp"/><path class="r-3kyjjbc"/><path class="nx38k027i"/><path class="zwxfjebkz"/><path class="z4w70fy1k"/><path class="q3dr23i2i"/><path class="tog720bax"/><path class="quauwu6ry"/><path class="rwhno3bam"/><path class="ipecv24vq"/><path class="b7uz81b5d"/><path class="hlzx1jbep"/><path class="tk2ldt9_j"/><path class="topaw4f1u"/><path class="e50dm2flj"/><path class="mu9r35btu"/><path class="w9p0k0b7q"/><path class="vbfn75h3y"/><path class="x96l0r40w"/><path class="ulbxc6b_n"/><path class="jnrn9kbku"/><path class="g1tufm8ue"/><path class="m38ptk52y"/><path class="xi4nii9ec"/><path class="ab07hubyl"/><path class="ln4do8qgn"/><path class="lqnz3bbiu"/><path class="jp8l0q4gg"/><path class="qfqkr77ru"/><path class="k5z_94b-s"/><path class="jn-0nfbid"/><path class="brcl0ebwq"/><path class="a1d30sb2n"/><path class="yvu0ngy8a"/><path class="om-a9lk2v"/><path class="kbw35nbug"/><path class="tcxguub1h"/><path class="vjooj0dxm"/><path class="tbredts0m"/><path class="blh9y3bzt"/><path class="e637whb_a"/><path class="kdu15blfk"/><path class="f0-h3_7yx"/><path class="zb2ikq3tj"/><path class="efh91tbou"/><path class="ayjofnbzp"/><path class="bjyfju5dr"/><path class="ylb-8cbzj"/><path class="whcz66qsa"/><path class="dzgpn0-or"/><path class="n21_qcb1x"/><path class="h_885vmuf"/><path class="ev94sobpy"/><path class="xph-qr12w"/><path class="hymduwbkb"/><path class="mbgct9b1n"/><path class="dl1ghxb8x"/><path class="x7xqgll8h"/><path class="wc6qwac-t"/><path class="focyf2spx"/><path class="jzd844bmp"/><path class="zgbg7wxys"/><path class="a7_eoub2x"/><path class="d5orc5bll"/><path class="l1f2wnhzr"/><path class="cjoosihwk"/><path class="x0yq5hb1v"/><path class="xg9rdef8p"/><path class="rld3kzkak"/><path class="pw5cswn1y"/><path class="gzmd5_bfg"/><path class="q52kyabba"/><path class="mol7zdbsj"/><path class="tk-fmqcmj"/><path class="oqxy3bb3h"/><path class="vowd7abck"/><path class="gs85ckbmj"/><path class="bql-c0zhx"/><path class="covclsbil"/><path class="trlmgccva"/><path class="qvucqnv_q"/><path class="aql08oj_k"/><path class="gm6o-nbns"/><path class="tcgq7uj8p"/><path class="j_z1-rbia"/><path class="go6u9cfta"/><path class="zj6zbtbcv"/><path class="mwkku3bjm"/><path class="j8smd0bse"/><path class="kjo930nae"/><path class="zbs650pwr"/><path class="f0ektffiu"/><path class="g-rcnd5zi"/><path class="azjyewbqi"/><path class="r_zgk4bgl"/><path class="dbkpw-bkk"/><path class="v06u8qbeg"/><path class="e6nr99bqs"/><path class="k1i7ntb-h"/><path class="ldx1j6tus"/><path class="jpjftmfng"/><path class="gls0qebpm"/><path class="uscjbyb-t"/><path class="p1lciv31g"/><path class="b1-_jy6sg"/><path class="n7p52ub7s"/><path class="ly9_xca6k"/><path class="vnti5abcq"/><path class="pqnngwnwe"/><path class="x0-1cdcbi"/><path class="r_h3nkgib"/><path class="c1bty7b-w"/><path class="j-jjlr4yb"/><path class="j1v6oibil"/><path class="jaomd_1iy"/><path class="oq3eq2bll"/><path class="bcv-jdbcd"/><path class="snq8c9ydp"/><path class="rrtnijb0p"/><path class="gt9c1u9dz"/><path class="j-vm7rbpl"/><path class="uk4434bff"/><path class="j4rovw-7p"/><path class="zys377bau"/><path class="f82jkkbvz"/><path class="jwgni_but"/><path class="w2hpek78g"/><path class="qs3-5rbrn"/><path class="t_sj99vdo"/><path class="iq6pat77x"/><path class="dlnnw2y8u"/><path class="ko55yxj_a"/><path class="rodcyu01h"/><path class="ykv5f1bgv"/><path class="dr4ysolhv"/><path class="t7vte7bed"/><path class="znahiqbbm"/><path class="beaq7acmp"/><path class="dlsqpmbnb"/><path class="yzsk2mbgw"/><path class="inuv-zqrf"/><path class="bpilz8jfi"/><path class="i7t8-k_pz"/><path class="wuxfuqbud"/><path class="h4bwyxqot"/><path class="btbkr2-7p"/><path class="s8ym8nb7u"/><path class="wqd48sb-y"/><path class="bspjllbsr"/><path class="dnaqjv-zb"/><path class="g65j30b_v"/><path class="z7hff9b-g"/><path class="p7mk8nyew"/><path class="ps_m-qbkv"/><path class="v3--swbew"/><path class="pv8xtub5m"/><path class="aqe82qc7b"/><path class="v7x-myklw"/><path class="k5kz1bbzq"/><path class="wahgfab9w"/><path class="ns5y8l9bc"/><path class="nh4_rd0gk"/><path class="guwl-zb7l"/><path class="f94sl6b1k"/><path class="ehs2m92oq"/><path class="c1a44bcul"/><path class="kxy05tb3t"/><path class="h3-bdabry"/><path class="yiul04bqh"/><path class="sdqa_hbvl"/><path class="djbbiu3yn"/><path class="aroyusbsm"/><path class="i_0x6cbmv"/><path class="dju5lvbvw"/><path class="kxgdms20o"/><path class="x4r4a_iol"/><path class="bzf5jjgzb"/><path class="p3m6o55dy"/><path class="xqg72jbcg"/><path class="np3e_pbxn"/><path class="r3u4__vgv"/><path class="vbs4ybdyb"/><path class="xewd65b6u"/><path class="jn2d19bso"/><path class="sopzmt9hv"/><path class="guc_3ccuv"/><path class="mi-8zoies"/><path class="hko_mcc0d"/><path class="i_3c4qsje"/><path class="h01_bchli"/><path class="bfcvg27ev"/><path class="gz38atbeh"/><path class="e_0fdenpd"/><path class="zkt--k02j"/><path class="egyek5y5l"/><path class="i_ij31bgc"/><path class="c5bribbsc"/><path class="q7sbiob4m"/><path class="c5je_yb2p"/><path class="zweyqt6oe"/><path class="m244qkbyw"/><path class="ce9xpwwue"/><path class="yfti8qnhw"/><path class="vadu-9eyl"/><path class="dgdzfgbub"/><path class="gb8owv85s"/><path class="ndjrrhjda"/><path class="e65gblb8p"/><path class="fifluib2u"/><path class="he03zmb8h"/><path class="byv90hb-f"/><path class="kt9dtutxd"/><path class="q8t8ivbou"/><path class="rgypmzbcu"/><path class="lqchn_73n"/><path class="tn69im68l"/><path class="gz-h53bgy"/><path class="yze4cj5vg"/><path class="c-9605f9s"/><path class="gip_v8x0v"/><path class="xvhnb-l4j"/><path class="xtjzcheyy"/><path class="yk8sn5bzh"/><path class="mbu2x9h4b"/><path class="p04z3abwk"/><path class="bsvyafb_q"/><path class="zwcg4qb0x"/><path class="wawaiccjf"/><path class="ngyq4ss7w"/><path class="t_eecl_wr"/><path class="l_vn41byo"/><path class="qv9u9j1fp"/><path class="ufb7rgbyc"/><path class="dxas3gbly"/><path class="bgmupeb6x"/><path class="gp8w6tb_d"/><path class="kklesxblf"/><path class="u6kk8lbza"/><path class="gnmnz5bpo"/><path class="i-byz-b1r"/><path class="ms_01bbxd"/><path class="yd6bwobfd"/><path class="m3qm09bpb"/><path class="zp_krbe0q"/><path class="ni5guwb0q"/><path class="ih-6ybccn"/><path class="ua6b9y3vh"/><path class="offl7bbly"/><path class="zo7j-nbdd"/><path class="w4k8-n-nx"/><path class="jrbqsebyd"/><path class="n8ub_3pmq"/><path class="k8qlllb4h"/><path class="djm65obao"/><path class="g7mzwabfs"/><path class="v1c8rob_k"/><path class="lqd0s51mx"/><path class="ynajhot_m"/><path class="wt_vf76hl"/><path class="k8dwd8avu"/><path class="gwkjy48_m"/><path class="c225ocbvp"/><path class="bcx4tx1fn"/><path class="a-7_ovbpw"/><path class="b5ypadbzw"/><path class="yk6lmckem"/><path class="kjldfwbgm"/><path class="pa6lxsbms"/><path class="i-145dwxn"/><path class="h9sccccqu"/><path class="igqn6079d"/><path class="su2jtum9t"/><path class="shv5b-b4z"/><path class="sr7fn6xaq"/><path class="qr9bhtvsx"/><path class="yobqttm_t"/><path class="do5h9ub3l"/><path class="ov6981bcd"/><path class="w35_yls4a"/><path class="mzhvzqb3o"/><path class="fc89wobwy"/><path class="hg-qz3bpo"/><path class="x2cfvgb5f"/><path class="x0hsrlb3y"/><path class="qe2sl7f0h"/><path class="q6cbv9w0w"/><path class="ckvg64bhl"/><path class="mxe3os-yu"/><path class="xzabp8bsg"/><path class="uguzfczxn"/><path class="ezjfmg7zp"/><path class="hfg-o_b1w"/><path class="zlw4xvb0u"/><path class="l-k1ljb-o"/><path class="mui9l5-mg"/><path class="m3f1kjb_a"/><path class="tbbt3ofnj"/><path class="bwxyebbul"/><path class="vxgvyeb5d"/><path class="ezv-bmbbz"/><path class="nnvzshixl"/><path class="bmsrgfmzf"/><path class="ous-fqbfs"/><path class="p_e7lzcsr"/><path class="byjwg03lt"/><path class="unflzxbds"/><path class="hx9f79wlb"/><path class="h2m0xq7hm"/><path class="u6lvlp4ai"/><path class="lad4txbqk"/><path class="dtlgspbsn"/><path class="ucq-o_bmz"/><path class="oysgywcay"/><path class="s83r-r71n"/><path class="d5419nuit"/><path class="r-l-fpmfg"/><path class="mh0k2dbnc"/><path class="zyett0myk"/><path class="y-hte9nmj"/><path class="y2bl9cb3n"/><path class="d0bja51rm"/><path class="ygxs8yhql"/><path class="b3fyztb4j"/><path class="xzu6n4bum"/><path class="del0lbcwh"/><path class="wxk_5ybpt"/><path class="uph-t29kf"/><path class="f50u_nbnm"/><path class="vd0pt8b4z"/><path class="gq9jm2bqd"/><path class="aw2ce5bab"/><path class="zmpdg21qa"/><path class="tnbwsfb5d"/><path class="p3qnyw91p"/><path class="sx3wyse7r"/><path class="ruxtncbdw"/><path class="zt_d_0ysi"/><path class="ys5r4cwub"/><path class="h82wwhbpo"/><path class="vt687uk4p"/><path class="sc6y04bri"/><path class="q4tvyygek"/><path class="j8r9qxb-v"/><path class="yr6cfor_h"/><path class="jf0xnkshr"/><path class="e8bdb2b6e"/><path class="ysulw4xmy"/><path class="wyue6kq7w"/><path class="al0tgqbht"/><path class="rj833nb5x"/><path class="l0gxh6l2g"/><path class="g1ivi6hym"/><path class="gvqk34y-e"/><path class="jbp9q88sd"/><path class="edgof_d7u"/><path class="fugoczbya"/><path class="l3a-fxb9z"/><path class="ie0y2r3se"/><path class="h_g8_0qqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-dominican-republic" /></template>
<style>
.a-7_ovbpw {
  fill: var(--svg-color--0c355d, #0c355d);
  d: path("M34.411 26.747v.168c.015.078-.004.121-.093.08q-.044.002-.084.009c-.053.026-.108.052-.144-.013c-.047-.085.026-.119.081-.159c.081-.028.065-.106.083-.168q.08.04.157.083");
}

.a1d30sb2n {
  fill: var(--svg-color--115e12, #115e12);
  d: path("M34.01 35.988c-.24-.009-.476-.036-.682-.165c.077-.142.158-.279.237-.42c.087-.066.163-.187.291-.063c.083.12.003.281.102.398c.042.079.094.156.052.25");
}

.a7_eoub2x {
  fill: var(--svg-color--b11a2a, #b11a2a);
  d: path("M36.564 36.32h.158c-.258.137-.302.564-.701.502c-.151-.125-.005-.193.054-.282c.105-.112.247-.164.382-.231a.13.13 0 0 1 .107.011");
}

.ab07hubyl {
  fill: var(--svg-color--941320, #941320);
  d: path("M31.751 37.23c-.033-.164-.111-.32-.081-.497c.104-.095.238-.093.367-.113a1 1 0 0 1 .107.032c.07.043.141.073.091.188c-.029.062-.187.006-.114.109c.052.074.168.11.214-.041c.016-.055.058-.092.115-.112q.07.004.096.066c.065.134.058.255-.05.364l-.104.076c-.122.15-.265.057-.401.035c-.101.014-.163-.061-.24-.107");
}

.al0tgqbht {
  fill: var(--svg-color--676364, #676364);
  d: path("M31.516 32.33q.121 0 .244.003l-.031.634c-.096-.12-.044-.261-.056-.394c-.026-.233-.155-.11-.259-.078c.016-.065.006-.149.102-.165");
}

.aqe82qc7b {
  fill: var(--svg-color--0f6f15, #0f6f15);
  d: path("M28.512 36.16c-.113-.138-.292-.032-.422-.111c.084-.168.422-.186.285-.496c-.017-.035.146-.006.209-.063l.255-.084c.146.156.211.324.078.523c-.068.095-.246.014-.273.174z");
}

.aql08oj_k {
  fill: var(--svg-color--1f2e41, #1f2e41);
  d: path("M34.571 27.413c.167-.008.316.029.426.165c-.141.031-.298.044-.325.237c-.197-.091.09-.307-.101-.402");
}

.aroyusbsm {
  fill: var(--svg-color--1a1c05, #1a1c05);
  d: path("M32.09 36.646q-.001-.034-.005-.07c.227.005.455-.045.668.073l-.345.024c-.105.077-.212.027-.318.002z");
}

.aw2ce5bab {
  fill: var(--svg-color--f4f3ef, #f4f3ef);
  d: path("M32.5 31.409q-.04-.038-.082-.082c0-.079-.027-.143-.103-.18c.055-.079.105-.157.16-.235c.028-.04.06-.079.088-.116c.264.18.115.438.106.662c-.002.051-.107-.04-.169-.049");
}

.ayjofnbzp {
  fill: var(--svg-color--087f30, #087f30);
  d: path("M27.326 29.329c-.127.109-.012.222-.007.334c.011.179-.06.318-.263.342l-.05-.014a.96.96 0 0 1 .153-.729c.128-.177.153-.06.167.067");
}

.azjyewbqi {
  fill: var(--svg-color--0b2749, #0b2749);
  d: path("M32.922 27.18q-.004-.05-.004-.1c.275.047.573-.105.829.1z");
}

.b1-_jy6sg {
  fill: var(--svg-color--0a274b, #0a274b);
  d: path("M29.424 27.18c.25-.165.5-.146.753-.006q-.377.002-.753.006");
}

.b3fyztb4j {
  fill: var(--svg-color--565656, #565656);
  d: path("M32.733 31.993c-.06-.076.016-.234-.149-.248c-.072-.039-.108-.104-.132-.18a.25.25 0 0 1 .025-.166c.132-.186.102-.396.086-.604l.007-.135c.043-.025.09-.049.132-.076c.117.469.05.94.031 1.409");
}

.b5ypadbzw {
  fill: var(--svg-color--16365f, #16365f);
  d: path("M31.17 33.8c.159-.222.072-.474.084-.711c-.128-.144-.113-.306-.065-.473a.25.25 0 0 1 .146-.143a.15.15 0 0 1 .119.047c.111.179.078.377.08.569c.002.19.044.355.216.465l.021.179c.029.085.056.172-.019.25c-.116.025-.057.174-.149.213c-.109-.089-.228-.063-.348-.029c-.126-.102.018-.262-.085-.367");
}

.b7uz81b5d {
  fill: var(--svg-color--177c2f, #177c2f);
  d: path("M27.09 33.26c.109.15.086.325.075.494c-.094.066-.091.19-.166.267a.3.3 0 0 1-.104.05a.7.7 0 0 1-.473-.06q-.02-.008-.035-.02c-.161-.113-.446-.227-.355-.42c.082-.178.363-.043.556 0c.098.04.195.076.297.02c.152-.079.111-.224.12-.352q.054-.038.085.021");
}

.bcv-jdbcd {
  fill: var(--svg-color--551119, #551119);
  d: path("m30.754 35.748l-.008.069c-.192.01-.386.033-.576-.026c.19-.07.387-.053.584-.043");
}

.bcx4tx1fn {
  fill: var(--svg-color--6a7036, #6a7036);
  d: path("M34.82 26.812c-.106.027-.195.076-.243.18c-.093.039-.149-.012-.199-.08c-.019-.061-.012-.118.033-.164c.161-.137.276.027.409.064");
}

.beaq7acmp {
  fill: var(--svg-color--605153, #605153);
  d: path("m33.981 37.16l-.075.246c-.126-.119-.103-.237 0-.357z");
}

.bfcvg27ev {
  fill: var(--svg-color--ca7e0c, #ca7e0c);
  d: path("M32.4 30.06c.149-.387.379-.726.601-1.069q.058-.038.103.015c-.213.367-.396.753-.665 1.085z");
}

.bgmupeb6x {
  fill: var(--svg-color--c0a613, #c0a613);
  d: path("m31.17 26.08l.074.326c-.261-.115-.261-.115-.074-.326");
}

.bjyfju5dr {
  fill: var(--svg-color--0b7b2b, #0b7b2b);
  d: path("m28.919 35.28l-.002.033a.21.21 0 0 1-.07.157a.31.31 0 0 1-.279.079c-.174-.127-.38-.223-.42-.471c.043-.073.1-.125.194-.092c.223.038.377.214.577.294");
}

.blh9y3bzt {
  fill: var(--svg-color--0c2441, #0c2441);
  d: path("M30.979 28.497c-.711 0-1.425-.004-2.137.002c-.142 0-.305-.06-.422.088c-.041-.033-.118-.067-.119-.102c-.007-.137.111-.077.171-.077c.842-.002 1.685.005 2.526.009q.03.034.012.06q-.016.019-.031.02");
}

.bmsrgfmzf {
  fill: var(--svg-color--88b688, #88b688);
  d: path("M26.927 30.492c.05.023.098.05.147.073c-.007.096-.144.195.01.284c.022.07-.017.104-.077.126l-.082.009q.003-.247.002-.492");
}

.bpilz8jfi {
  fill: var(--svg-color--56882f, #56882f);
  d: path("M34.592 34.08q.047.046.095.097c-.017.087-.007.187-.095.247c-.025-.031-.053-.061-.075-.09z");
}

.bql-c0zhx {
  fill: var(--svg-color--308734, #308734);
  d: path("M34.418 34.915c-.004-.067-.011-.131-.077-.17l.176-.41c.072-.01.12 0 .075.09q.04.072.085.146l-.09.092c.002.121.019.255-.169.252");
}

.brcl0ebwq {
  fill: var(--svg-color--0f8538, #0f8538);
  d: path("M35.415 32.16c-.026-.054-.055-.108-.078-.161c.021-.149-.19-.172-.175-.319a.11.11 0 0 1-.014-.103a.2.2 0 0 1 .092-.059a.45.45 0 0 1 .326.087a.3.3 0 0 1 .078.084c.078.237.261.445.194.721c-.264.122-.235-.246-.423-.25");
}

.bspjllbsr {
  fill: var(--svg-color--97b376, #97b376);
  d: path("m35.08 31.425l.086.004c.044.048.057.093-.006.137l.011.012q-.032.037-.073.009q-.011-.083-.018-.162");
}

.bsvyafb_q {
  fill: var(--svg-color--425746, #425746);
  d: path("M28.753 26.822c.04-.114.13-.153.24-.167c.081.05.101.12.087.209c-.076.351-.233-.042-.338.035q-.036-.034-.02-.055q.015-.022.031-.022");
}

.btbkr2-7p {
  fill: var(--svg-color--211819, #211819);
  d: path("M37.25 35.29c.004-.091-.052-.124-.131-.14c.079-.092.214-.121.27-.047c.058.079-.087.126-.139.187");
}

.bwxyebbul {
  fill: var(--svg-color--026605, #026605);
  d: path("M35.25 30.665c-.059-.156-.11-.318-.243-.434a.25.25 0 0 1 .248-.149c.157.187.224-.011.323-.077c-.063.431.131.826.176 1.24c-.36-.027-.346-.379-.504-.58");
}

.byjwg03lt {
  fill: var(--svg-color--098539, #098539);
  d: path("M36 31.32c-.088.041-.175.083-.172-.076c.167-.164.217-.392.334-.58h.095c.104.19-.056.331-.093.496c-.035.073-.081.137-.164.16");
}

.byv90hb-f {
  fill: var(--svg-color--d8bb33, #d8bb33);
  d: path("M31.25 30.845c-.109.02-.165-.063-.231-.125l-.087-.228c.187-.009.181.192.287.266z");
}

.bzf5jjgzb {
  fill: var(--svg-color--db6714, #db6714);
  d: path("m28.842 36.491l-.091.184c-.071-.056-.19-.106-.111-.222c.058-.082.145-.041.202.038");
}

.c-9605f9s {
  fill: var(--svg-color--cd1227, #cd1227);
  d: path("M30.919 33.743c-.062.105-.087.246-.25.251a.93.93 0 0 1-.582 0c-.365-.072-.328-.447-.497-.667c-.098-.32-.018-.648-.045-.972c.067-.25.203-.104.287-.031c.262.236.548.456.692.792a.67.67 0 0 0 .395.389q.186.121 0 .238");
}

.c1a44bcul {
  fill: var(--svg-color--e2970a, #e2970a);
  d: path("M32.08 35.988c-.037.113.081.228-.002.341c-.244.004-.22-.282-.399-.35c.148-.17.265.148.401.009");
}

.c1bty7b-w {
  fill: var(--svg-color--a2b576, #a2b576);
  d: path("m34.827 32.821l.083.26q-.116.002-.232.008c-.019-.129-.043-.26.149-.268");
}

.c225ocbvp {
  fill: var(--svg-color--8d8628, #8d8628);
  d: path("M35.09 27.337c-.104-.098-.372-.072-.25-.335c.342-.081.322.107.25.335");
}

.c5bribbsc {
  fill: var(--svg-color--d0aa07, #d0aa07);
  d: path("M32.498 30.659a.3.3 0 0 0 .072.002c.054.033.063.083.059.141a.22.22 0 0 1-.098.124c-.068.029-.141-.021-.209.002c-.129-.211.029-.236.176-.269");
}

.c5je_yb2p {
  fill: var(--svg-color--cf800c, #cf800c);
  d: path("M32.438 30.09q-.102.219-.208.433c-.06-.209.04-.343.17-.463z");
}

.ce9xpwwue {
  fill: var(--svg-color--cfa907, #cfa907);
  d: path("M32.32 30.928c.041-.097.098-.052.153-.016c.093.175-.048.195-.16.235q-.033-.063-.07-.129z");
}

.cjoosihwk {
  fill: var(--svg-color--930d1c, #930d1c);
  d: path("M31.09 37.31h-.43q-.018-.024 0-.046l.014-.063c.146-.205.309-.355.581-.215l.009.015c.07.116.004.179-.09.229z");
}

.ckvg64bhl {
  fill: var(--svg-color--ebf3eb, #ebf3eb);
  d: path("m27.609 31.745l.08.165c-.162.133-.32.268-.357.492q-.041.052-.104.021c-.115-.074-.143-.188-.132-.316c.017-.12.089-.214.152-.312a.5.5 0 0 1 .157-.162a.1.1 0 0 1 .1.024q.03.014.063.009q.065.017.041.079");
}

.covclsbil {
  fill: var(--svg-color--e8ead5, #e8ead5);
  d: path("m36.419 34.637l.245-.063c-.006.145.511-.035.19.304q-.05.003-.103.002a.6.6 0 0 0-.106-.031c-.145-.023-.314.029-.415-.132c.033-.101.1-.114.189-.08");
}

.d0bja51rm {
  fill: var(--svg-color--4b8326, #4b8326);
  d: path("m36.33 34.888l-.079-.151c.161.069.384-.128.504.12c-.151-.103-.278.079-.425.031");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d5419nuit {
  fill: var(--svg-color--0b883f, #0b883f);
  d: path("m36 31.32l.079-.151c.137-.185.197-.412.339-.594l.158-.081l.012.182c.041.05.033.11.029.168a2.6 2.6 0 0 1-.281.564l-.002.006l-.168.078l-.261.215c.037-.161.067-.272.095-.387");
}

.d5orc5bll {
  fill: var(--svg-color--178435, #178435);
  d: path("m36.17 30.665l.08-.242c.146-.054.201-.212.318-.293c.156-.106.075.063.108.102c.06.094.039.184-.022.269a.6.6 0 0 1-.179.143a.5.5 0 0 1-.211.07a.15.15 0 0 1-.094-.049");
}

.dbkpw-bkk {
  fill: var(--svg-color--25893c, #25893c);
  d: path("M36.832 33q.145-.091.29-.178c.113-.07.123.004.13.088l-.241.243c-.09-.016-.14-.079-.179-.153");
}

.del0lbcwh {
  fill: var(--svg-color--9d8c3a, #9d8c3a);
  d: path("M31.16 29.579c.274-.043.347.084.345.344c0 .219-.087.457.072.663c-.039.059-.097.081-.167.075c.002-.222-.023-.447.013-.661c.039-.24-.091-.334-.263-.421");
}

.dgdzfgbub {
  fill: var(--svg-color--28424d, #28424d);
  d: path("m29.671 29.927l-.086-.271c.109-.058.079-.164.093-.257q.055-.039.102.017l.061.054c.013.152.145.196.244.271c.073.186.204.33.34.471c0 .083-.009.163-.079.224c-.38.036-.511-.261-.675-.509");
}

.djbbiu3yn {
  fill: var(--svg-color--d85219, #d85219);
  d: path("M29.991 36.17c-.151.092.028.346-.303.426c.22-.167.011-.457.323-.507q.037.054-.02.081");
}

.djm65obao {
  fill: var(--svg-color--bd1023, #bd1023);
  d: path("M36.17 36.573q-.127.003-.25.002c.05-.084.104-.167.152-.252c.14-.021.184-.182.322-.205c.131.013.175.072.112.194c-.041.181-.247.146-.336.261");
}

.dju5lvbvw {
  fill: var(--svg-color--e5a308, #e5a308);
  d: path("m32.913 36.22l-.136.119c-.058-.111-.011-.225-.006-.336l.142.095q.073.06 0 .122");
}

.dl1ghxb8x {
  fill: var(--svg-color--196a15, #196a15);
  d: path("M31.09 37.31c-.148.248-.42.283-.658.376c-.079-.033-.178-.043-.18-.162q.206-.106.408-.214q.216-.164.43 0");
}

.dlnnw2y8u {
  fill: var(--svg-color--c3e0cc, #c3e0cc);
  d: path("m35.08 30.915l-.246-.18q0-.079.004-.159c.132.077.227.179.242.339");
}

.dlsqpmbnb {
  fill: var(--svg-color--5b1111, #5b1111);
  d: path("m31.17 37.23l.09-.229l.159.226z");
}

.dnaqjv-zb {
  fill: var(--svg-color--598424, #598424);
  d: path("M36.914 30.563a.2.2 0 0 0-.006-.048c.061-.021.085.003.078.063a.2.2 0 0 1-.072-.015");
}

.do5h9ub3l {
  fill: var(--svg-color--9b8e22, #9b8e22);
  d: path("m33.926 26.954l-.009-.125l.178.003a.3.3 0 0 1 .077 0c-.055.084-.096.163.063.172c-.133.171-.207-.032-.309-.05");
}

.dr4ysolhv {
  fill: var(--svg-color--9abc95, #9abc95);
  d: path("M26.884 33.595c-.11.18-.203.068-.297-.02l.083-.08z");
}

.dt1ql-k8c {
  fill: var(--svg-color--026a0c, #026a0c);
  d: path("M34.677 34.571c.155-.162.156-.389.248-.579c.076-.087-.025-.286.181-.294c.236.05-.029-.126.059-.145q0-.09.035-.17c.035-.057.081-.09.151-.063c.046.046.06.104.066.163c.048.131.033.266.05.399c-.03-.463-.098-.921-.273-1.353c-.086-.217-.033-.34.193-.39c.188-.055.266.166.43.173c.07-.008.141-.031.211-.005q.073.044.106.122c.061.096-.051.236.086.313c.066.01.132.016.19.055c.076.146-.07.227-.094.344a1 1 0 0 1-.056.098c-.279.404-.352.922-.696 1.293c-.069.093-.127.199-.238.254c-.273.075-.27-.113-.263-.309a1.3 1.3 0 0 1-.11.245c-.08.141-.135.378-.312.343c-.218-.045-.056-.279-.094-.424c.024-.056.053-.105.13-.07");
}

.dtlgspbsn {
  fill: var(--svg-color--07873e, #07873e);
  d: path("M35.25 30.665c.243.127.268.445.504.58c-.085.126.243.425-.173.413l-.073.002a2.2 2.2 0 0 1-.334-.503l.006-.002l-.009-.173z");
}

.dxas3gbly {
  fill: var(--svg-color--1b3e56, #1b3e56);
  d: path("M31.17 26.08c.077-.061.132-.178.259-.08c.056.132.039.266.012.399l-.196.007c-.048-.103-.116-.203-.075-.326");
}

.dzgpn0-or {
  fill: var(--svg-color--138337, #138337);
  d: path("M27.757 29.26c.139.224.068.459-.135.519c-.244.075-.178-.244-.281-.367c.184.072.258-.154.416-.152");
}

.e_0fdenpd {
  fill: var(--svg-color--c17a0d, #c17a0d);
  d: path("M33.411 29.517q-.083.07-.16.141q-.032-.031-.027-.067q.01-.035.019-.036l.333-.488a.12.12 0 0 1 .094.096q-.132.175-.259.354");
}

.e50dm2flj {
  fill: var(--svg-color--0b741c, #0b741c);
  d: path("M35.08 28.921c.198.325.379.66.513 1.019a.16.16 0 0 1 .004.118c-.101.171-.219.233-.378.065c.014-.233-.201-.329-.302-.493a.5.5 0 0 1-.05-.222c.053-.133.093-.272.094-.419c.018-.059.044-.105.119-.068");
}

.e637whb_a {
  fill: var(--svg-color--1b8337, #1b8337);
  d: path("M26.323 32.663a9 9 0 0 1-.231-.145c.177-.118-.027-.139-.059-.176c-.174-.209.037-.163.122-.201c.139-.043.279-.012.418-.022a.16.16 0 0 1 .11.029a.15.15 0 0 1 .007.11c-.105.076-.105.121 0 .287c-.08.177-.255.046-.367.118");
}

.e65gblb8p {
  fill: var(--svg-color--90821f, #90821f);
  d: path("M30.667 30.58a.1.1 0 0 1-.07.021a.5.5 0 0 1-.102.024a.2.2 0 0 1-.101-.022c-.059-.048-.1-.104-.091-.182l.12-.21c.126.094.223.206.244.369");
}

.e6nr99bqs {
  fill: var(--svg-color--166f11, #166f11);
  d: path("m36.01 29.747l.231.037l-.155.204q-.086.084-.176.167c-.041-.057-.046-.117-.001-.177q.047-.117.101-.231");
}

.e8bdb2b6e {
  fill: var(--svg-color--c11025, #c11025);
  d: path("M31.745 33.555c-.222.067-.336.009-.323-.247c.014-.271 0-.545-.002-.816l-.006.003c.146-.162.265-.214.294.075c.012.132-.018.266.021.396c-.115.198.063.39.016.589");
}

.edgof_d7u {
  fill: var(--svg-color--01873e, #01873e);
  d: path("m35.686 35.15l-.104-.07c.096-.116.221-.079.344-.062z");
}

.efh91tbou {
  fill: var(--svg-color--088236, #088236);
  d: path("M26 31.493c.065.182.505.306.092.564c-.199-.139-.462-.247-.27-.571z");
}

.egyek5y5l {
  fill: var(--svg-color--ba800c, #ba800c);
  d: path("M33.418 29.953c-.08-.073-.004-.136.021-.2l.308-.345q.082.092.009.193l-.111.174z");
}

.ehs2m92oq {
  fill: var(--svg-color--d12621, #d12621);
  d: path("M33.06 36.408c-.153.102-.308.139-.467.013v-.031c.092-.12-.016-.277.077-.396l.104.013c.06.055-.002.205.15.19c.1.005.147.072.187.151q.014.063-.051.06");
}

.ev94sobpy {
  fill: var(--svg-color--07883f, #07883f);
  d: path("M33.836 35.41c.164-.063.287-.169.329-.347q.09-.157.176-.318c.116-.018.125.066.137.145c-.111.313-.267.6-.504.836q-.03.01-.057.016c-.288-.048-.04-.223-.081-.332");
}

.ezjfmg7zp {
  fill: var(--svg-color--026a0c, #026a0c);
  d: path("M36.584 32.25c-.04.248-.236.364-.416.496c.078-.217.141-.446.416-.496");
}

.ezv-bmbbz {
  fill: var(--svg-color--dbe3cc, #dbe3cc);
  d: path("m35.34 33.16l-.091-.002c-.034-.068-.065-.139-.157-.145c-.153-.112-.033-.24-.024-.362c.052-.126.122-.163.179-.011c.061.167.116.337.093.52");
}

.f_mei872j {
  fill: var(--svg-color--042f61, #042f61);
  d: path("M30.919 27.1c-.231.18-.485.141-.742.075a1.08 1.08 0 0 0-.753.006l-.89.237c-.144.12-.316.199-.461.317a.5.5 0 0 1-.259.13c-.273-.025-.3-.281-.425-.449c-.148-.256.067-.34.222-.434a4.05 4.05 0 0 1 2.06-.621c.15.037.345-.048.438.154a.5.5 0 0 1 .046.104c.035.103.03.227.17.262c.07.014.144.013.217.008c.135.005.279-.086.403.033a.2.2 0 0 1-.026.178");
}

.f0-h3_7yx {
  fill: var(--svg-color--0d7825, #0d7825);
  d: path("M27.596 31.19q0-.04-.006-.08c-.057-.121-.001-.203.086-.278c.401.227.592-.021.757-.331c-.026.123.253.061.137.225c-.115.165-.24.343-.466.361c-.176.016-.356-.016-.508.103");
}

.f0ektffiu {
  fill: var(--svg-color--138337, #138337);
  d: path("M27.836 29.897c.07-.167.03-.424.328-.401a.66.66 0 0 1-.328.401");
}

.f50u_nbnm {
  fill: var(--svg-color--9f9877, #9f9877);
  d: path("M31.654 30.568c.076-.292-.094-.613.099-.895c.027.247-.074.508.085.739z");
}

.f82jkkbvz {
  fill: var(--svg-color--8fba8f, #8fba8f);
  d: path("M26.685 32.13c-.173.076-.353.011-.529.016a.1.1 0 0 1 .004-.046l.461-.018q.05.003.064.048");
}

.f94sl6b1k {
  fill: var(--svg-color--dc6e13, #dc6e13);
  d: path("M34.02 36.724c-.415-.073-.38-.237-.194-.479c.131.127.101.291.194.479");
}

.fc89wobwy {
  fill: var(--svg-color--b9ceb3, #b9ceb3);
  d: path("M27.09 33.26q-.042-.013-.086-.021a.57.57 0 0 0-.168-.335l-.002.005c.047-.055.084-.127.178-.117c.143.039.235.123.242.279c-.033.081-.077.154-.164.189");
}

.fifluib2u {
  fill: var(--svg-color--a69214, #a69214);
  d: path("M29.14 29.27c.184.053.312.083.322.25c0 .023-.054.069-.084.069c-.174.01-.17-.137-.238-.319");
}

.focyf2spx {
  fill: var(--svg-color--2b8a3a, #2b8a3a);
  d: path("M36.501 32.742c.059-.257.209-.41.483-.415c.04.15-.15.2-.15.332c-.062.143-.19.162-.322.172q-.047-.024-.035-.056q.01-.032.024-.033");
}

.fugoczbya {
  fill: var(--svg-color--72a872, #72a872);
  d: path("M27.08 31.813q-.015-.027.007-.052c-.019-.12.16-.07.157-.176c.073-.004.144.006.183.081l-.096.141c-.081.048-.163.092-.251.006");
}

.g-rcnd5zi {
  fill: var(--svg-color--132439, #132439);
  d: path("m30.08 26.03l.005.549c-.091-.168-.275-.151-.416-.222c.258.043.332-.145.411-.327");
}

.g1ivi6hym {
  fill: var(--svg-color--234a77, #234a77);
  d: path("m31.08 33l.012.268a.3.3 0 0 1-.024.078c-.11-.011-.254-.017-.259-.141c-.004-.145.182-.128.271-.205");
}

.g1tufm8ue {
  fill: var(--svg-color--c51024, #c51024);
  d: path("m28.26 37.498l-.006-.089c.299-.215.688-.271.95-.548c.04-.041.103-.005.138.048l-.045.146c.01.126-.096.187-.156.275c-.1.123-.238.19-.383.248c-.185.09-.348.048-.498-.08");
}

.g65j30b_v {
  fill: var(--svg-color--046400, #046400);
  d: path("m36.4 29.825l-.065-.076c.052 0 .084.016.065.076");
}

.g7mzwabfs {
  fill: var(--svg-color--91a46c, #91a46c);
  d: path("M35.501 35.914c-.154-.149-.313-.114-.478-.017c-.038-.004-.086.004-.113-.018c-.054-.045-.035-.092.028-.111c.135-.035.302.035.399-.123c.127-.063.207-.016.257.104q-.046.085-.093.165");
}

.gb8owv85s {
  fill: var(--svg-color--9b8a18, #9b8a18);
  d: path("m29.779 29.416l-.102-.017c-.111-.205-.408-.288-.378-.617c.33.094.338.418.48.634");
}

.gip_v8x0v {
  fill: var(--svg-color--fefdfd, #fefdfd);
  d: path("M29.02 32.15a95 95 0 0 1-.008-1.065c.391-.082.592.037.51.473c-.01.057.035.125.054.188c.054.155.057.3-.078.423a26 26 0 0 0-.478-.019");
}

.gls0qebpm {
  fill: var(--svg-color--194506, #194506);
  d: path("m30.567 36.896l-.182-.066c-.056-.149-.196-.068-.293-.107c.089-.084.202-.066.308-.079c.08-.031.155-.037.213.042a.35.35 0 0 1 .004.178z");
}

.gm6o-nbns {
  fill: var(--svg-color--498e3e, #498e3e);
  d: path("M37.35 34.01c-.019.225-.285.074-.352.229q.032.035.022.068q-.01.035-.019.036c-.068.019-.112-.017-.151-.066c-.041-.072-.074-.147-.019-.229c.064-.057.146-.074.226-.092c.098.014.21-.044.293.054");
}

.gnmnz5bpo {
  fill: var(--svg-color--baa315, #baa315);
  d: path("M32.13 26c.081.16.05.271.021.409c-.096-.136-.067-.247-.021-.409");
}

.go6u9cfta {
  fill: var(--svg-color--148338, #148338);
  d: path("M28.22 33.572c-.074-.12-.218.01-.3-.081c-.025-.109-.122-.248.105-.252c.116.08.227.165.195.333");
}

.gp8w6tb_d {
  fill: var(--svg-color--9b8f22, #9b8f22);
  d: path("M32.55 26.452c-.091-.069-.207-.088-.179-.214c.005-.028.069-.07.085-.064c.098.046.128.13.094.278");
}

.gq9jm2bqd {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("m31.849 31.946l-.019-.127c.062-.271.252-.412.502-.49l.086-.002a.1.1 0 0 1 .082.082q-.007.082-.01.162c-.122.282-.356.372-.641.375");
}

.gs85ckbmj {
  fill: var(--svg-color--0a741c, #0a741c);
  d: path("m36.75 34.478l-.086.096c-.043.1-.113.152-.228.125a.3.3 0 0 1-.093-.064c-.137-.139-.151-.26.058-.34c.124-.002.254-.057.372.033c.024.055.026.107-.023.15");
}

.gt9c1u9dz {
  fill: var(--svg-color--b62d3c, #b62d3c);
  d: path("M32.661 37.24c.181.021.137-.225.288-.239c-.087.091.125.54-.288.239");
}

.guc_3ccuv {
  fill: var(--svg-color--fcfcfb, #fcfcfb);
  d: path("m31.02 28.497l1.062.006q-.003.413-.002.824c-.172.146-.3.054-.422-.072c-.037-.035-.081-.044-.127-.017c-.06.117-.246.12-.248.284q.041.04.083.07c.277.318.158.68.124 1.031a.28.28 0 0 1-.19.163c-.228.033-.226-.217-.364-.295c.148-.658.022-1.33.084-1.994");
}

.guwl-zb7l {
  fill: var(--svg-color--076a1a, #076a1a);
  d: path("M29.424 35.929c-.151-.027-.199-.153-.254-.27c.093-.045.058-.134.055-.22c.193.054.045.238.168.315c.019-.1.038-.192.059-.307c.22.121-.025.335.136.44a3 3 0 0 1-.164.042");
}

.gvqk34y-e {
  fill: var(--svg-color--0c6d0e, #0c6d0e);
  d: path("M35.686 35.15q.033.052.064.105q.042.025.027.05q-.014.023-.029.023h-.651c.209-.107.347-.179.487-.249h-.002c.077-.039.1.004.104.071");
}

.gwkjy48_m {
  fill: var(--svg-color--1e2f44, #1e2f44);
  d: path("M35.08 27.992c-.011-.328.192.025.25-.078c-.06.099-.156.081-.25.078");
}

.gz-h53bgy {
  fill: var(--svg-color--a4a5a7, #a4a5a7);
  d: path("M33.588 32.17c-.033-.118.046-.267-.095-.358c.209-.206.009-.51.173-.726q.009.53.011 1.06z");
}

.gz38atbeh {
  fill: var(--svg-color--988a48, #988a48);
  d: path("m32.01 29.647l-.037.015l-.04-.009c-.18-.15-.452-.258-.29-.581c.108.149.193.338.436.255a.4.4 0 0 1-.069.32");
}

.gzmd5_bfg {
  fill: var(--svg-color--64141d, #64141d);
  d: path("M28.762 37.491c-.062.117-.041.185.109.171a.79.79 0 0 1-.792-.003c.085-.024.275.066.179-.161a.8.8 0 0 0 .504-.007");
}

.h_885vmuf {
  fill: var(--svg-color--236f1a, #236f1a);
  d: path("m31.991 37.34l.401-.035c.058.038.119.068.169.114c.09.078.34.058.236.247c-.062.112-.248.011-.359-.047c-.158-.078-.299-.183-.447-.279");
}

.h_g8_0qqo {
  fill: var(--svg-color--b81628, #b81628);
  d: path("m31.09 32.593l.02.146c-.526.068-.188-.327-.268-.497z");
}

.h01_bchli {
  fill: var(--svg-color--f8f8f8, #f8f8f8);
  d: path("m32 30.994l.098-.015l.146.039c.063.034.126.063.173.118c.047.064.06.13.016.202a.3.3 0 0 1-.099.047c-.245-.005-.396.178-.577.297a.14.14 0 0 1-.11-.016a.42.42 0 0 1-.095-.268c.076-.213.296-.272.448-.404");
}

.h2m0xq7hm {
  fill: var(--svg-color--8db98d, #8db98d);
  d: path("M27.01 30.976q.04-.063.077-.126q.166-.008.331-.019c-.079.115-.216.113-.327.165q-.039-.012-.081-.02");
}

.h3-bdabry {
  fill: var(--svg-color--de7a11, #de7a11);
  d: path("M33.17 36.408c.144.007.216-.098.299-.248c.023.161.041.265.063.403c-.175-.037-.349-.007-.479-.155l.031.002q.04-.061.086-.002");
}

.h4bwyxqot {
  fill: var(--svg-color--703b41, #703b41);
  d: path("M33.575 36.829c.141.001.315-.061.34.171z");
}

.h82wwhbpo {
  fill: var(--svg-color--cca40a, #cca40a);
  d: path("M30.846 31.1c-.075-.043-.135-.102-.148-.192c.084-.068.154-.027.227.021c.003.069-.018.13-.079.171");
}

.h9sccccqu {
  fill: var(--svg-color--007017, #007017);
  d: path("M36.82 33.497h.084l.091.094c-.139.055-.279.111-.451.182c.04-.21.186-.208.276-.276");
}

.he03zmb8h {
  fill: var(--svg-color--c3a409, #c3a409);
  d: path("M30.08 29.02c-.183-.041-.167-.174-.15-.32c.141.009.205.089.228.213c-.023.036-.03.088-.078.107");
}

.hfg-o_b1w {
  fill: var(--svg-color--e9f1e9, #e9f1e9);
  d: path("m26.685 32.13l-.064-.048c-.041-.08.107-.182-.024-.252l.135-.314c.133.024.18.117.188.24c-.031.165-.004.367-.245.407l.018-.012z");
}

.hg-qz3bpo {
  fill: var(--svg-color--e4e9de, #e4e9de);
  d: path("M36.753 34.856v.022l-.431.495c-.052.105-.132.016-.197.029c-.128-.037-.233-.146-.381-.123c-.067-.012-.104-.052-.102-.122c.053-.126.169-.176.28-.229c.137-.052.272-.102.422-.102c.137.019.284-.125.41.03");
}

.hgpfamceb {
  fill: var(--svg-color--042e5f, #042e5f);
  d: path("M35.946 27.653c.348.083.688.181.97.418c.045.169-.093.115-.169.132c-.08.017-.211-.036-.176.133c.031.097.124.178.076.335c-.474-.344-1.061-.348-1.562-.594q-.032-.033-.022-.068q.007-.037.018-.037c.073-.066.17-.1.245-.165c.175-.181.374-.259.62-.154");
}

.hko_mcc0d {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M32.06 30.572a8 8 0 0 0-.228-.159c-.288-.19-.202-.455-.143-.716c.039-.07.105-.096.18-.099a.2.2 0 0 1 .133.049c.164.3.062.616.058.925");
}

.hlzx1jbep {
  fill: var(--svg-color--037e30, #037e30);
  d: path("m26.332 31.13l.185-.3c.201-.109.305.049.427.156a.33.33 0 0 1 .04.243a1.1 1.1 0 0 1-.156.344c-.093.119-.134.293-.331.299c-.375-.174-.305-.45-.165-.742");
}

.hr7cw47jv {
  fill: var(--svg-color--c32129, #c32129);
  d: path("M0 37v6c0 6.075 3.373 11 10 11h16V37zm54-27H37v17h27v-6c0-6.075-3.373-11-10-11");
}

.hx9f79wlb {
  fill: var(--svg-color--b61022, #b61022);
  d: path("m32.09 36.675l.318-.002l.024.137c-.017.117-.085.225-.009.463a1.3 1.3 0 0 0-.643-.324c.079-.185.223-.089.324-.127c.179-.062-.019-.095-.014-.147");
}

.hymduwbkb {
  fill: var(--svg-color--a72533, #a72533);
  d: path("M26.514 36.39q.12-.03.24-.063c.111-.01.185.05.253.125c.063.122.299.172.156.378c-.352.054-.497-.2-.649-.44");
}

.i_0x6cbmv {
  fill: var(--svg-color--e2930b, #e2930b);
  d: path("m30.866 36.02l.183.387c-.225-.084-.243-.199-.183-.387");
}

.i_3c4qsje {
  fill: var(--svg-color--1d3b52, #1d3b52);
  d: path("M33.418 29.953c-.203.164-.306.464-.628.462c-.102-.04-.083-.102-.033-.168l-.003.002c.068-.145.218-.226.292-.364c.031-.107.118-.171.19-.245c.076-.016.028-.207.175-.123q.012.118.028.236c.008.068-.041.13-.021.2");
}

.i_ij31bgc {
  fill: var(--svg-color--d29807, #d29807);
  d: path("m33.669 29.16l-.094-.093c.021-.133.104-.277.22-.187c.105.084-.006.219-.126.28");
}

.i-145dwxn {
  fill: var(--svg-color--006809, #006809);
  d: path("M36.25 34.24c-.141.218-.367.226-.59.253c.14-.222.351-.267.59-.253");
}

.i-byz-b1r {
  fill: var(--svg-color--968c24, #968c24);
  d: path("M30.758 26.26c.013-.08.059-.159-.009-.236c.088-.02.173-.027.179.096c.004.113-.091.119-.17.14");
}

.i7t8-k_pz {
  fill: var(--svg-color--026707, #026707);
  d: path("M28.25 30.401c-.053.078-.117.173-.221.099c-.056-.039-.017-.125.044-.172c.031.095.109.07.177.073");
}

.ie0y2r3se {
  fill: var(--svg-color--666, #666);
  d: path("M30.585 31.658c-.052-.024-.104-.054-.155-.079q0-.13.004-.256a.57.57 0 0 1 .151.335");
}

.igqn6079d {
  fill: var(--svg-color--028033, #028033);
  d: path("M27.833 35.907c.211-.128.107-.252-.006-.377l-.072-.363q.015-.085.095-.091q.086.04.17.076c.049-.024.099-.052.148-.076l.416.415c-.054.05-.164.127-.155.143c.161.305.166.303-.19.36c-.05.008-.1.037-.148.056c-.097-.03-.217-.012-.258-.143");
}

.ih-6ybccn {
  fill: var(--svg-color--9dae69, #9dae69);
  d: path("m35.03 33.24l.054-.088c.215-.002.095.188.154.273q.006.076.009.151c-.032.029-.041.087-.098.093a21 21 0 0 0-.119-.429");
}

.il0tzxo5v {
  fill: var(--svg-color--012e61, #012e61);
  d: path("M28.892 29.09q-.234-.25-.472-.498c.027-.243.216-.123.321-.125c.722-.011 1.442-.008 2.162-.006a.17.17 0 0 1 .134.054c.16.626.085 1.255.04 1.885c-.029.109.012.218.006.327c-.008.084-.026.163-.118.201c-.159-.051-.228-.197-.33-.308a1.4 1.4 0 0 0-.27-.331a1.6 1.6 0 0 1-.35-.472c-.057-.111-.147-.196-.23-.287a.5.5 0 0 1-.073-.146c-.061-.136-.177-.228-.281-.422c.106.227.276.326.3.519c.022.117-.023.222-.073.325c-.074.287-.024.579-.042.868c-.014.255-.099.433-.393.418c-.289-.012-.262-.221-.261-.418c.002-.443.005-.885-.001-1.328c0-.086.051-.198-.069-.256");
}

.inuv-zqrf {
  fill: var(--svg-color--88a75f, #88a75f);
  d: path("M35.01 29.01a.3.3 0 0 1-.079-.008c.021-.081-.111-.185.012-.233c.063-.022.136.058.138.148c-.059.006-.07.046-.071.093");
}

.ipecv24vq {
  fill: var(--svg-color--068a43, #068a43);
  d: path("M36.17 32.831c-.139.108-.168.027-.151-.098c.013-.106.044-.215.066-.322c-.048-.095-.007-.182.027-.27c.106-.166.142-.383.329-.5c.195.063.136-.248.313-.215q.192-.139.384-.275q.214-.034.106.153c-.079.072-.17.134-.164.259c-.076.148-.117.314-.237.436c-.075.117-.098.273-.253.33c-.187.078-.248.264-.346.417z");
}

.iq6pat77x {
  fill: var(--svg-color--3d3936, #3d3936);
  d: path("M26.492 28.462q.037.058.079.114c-.055.128-.164.146-.365.208c.14-.156.212-.239.286-.322");
}

.j_z1-rbia {
  fill: var(--svg-color--278330, #278330);
  d: path("m37.15 33.25l-.248.246q-.043.033-.084 0c-.152-.229.082-.25.186-.341z");
}

.j-jjlr4yb {
  fill: var(--svg-color--3c9042, #3c9042);
  d: path("M36.836 31.05c-.041-.176.049-.292.176-.395c.112.209-.062.289-.176.395");
}

.j-vm7rbpl {
  fill: var(--svg-color--460e15, #460e15);
  d: path("M36.17 36.573c-.041.089-.18.12-.146.248l-.181.013q.036-.13.077-.259c.082-.059.165-.076.25-.002");
}

.j1v6oibil {
  fill: var(--svg-color--4e852a, #4e852a);
  d: path("m37.12 32.751l-.118-.081c.058-.056.107-.118.171-.159c.046-.031.104-.122.162-.031c.05.079-.076.098-.081.166c.002.094-.019.159-.134.105");
}

.j4rovw-7p {
  fill: var(--svg-color--7d0c19, #7d0c19);
  d: path("M29.11 34.32c.17.047.283.145.307.328a.62.62 0 0 1-.307-.328");
}

.j8r9qxb-v {
  fill: var(--svg-color--3e3c3d, #3e3c3d);
  d: path("M32.32 31.98q-.162.088-.327.17c-.099.021-.194.016-.258-.081l.111-.123l.642-.375c.078.031.084.104.094.174z");
}

.j8smd0bse {
  fill: var(--svg-color--4f9243, #4f9243);
  d: path("M35.08 31.425c-.098-.094-.256-.161-.156-.344c.096-.099.17-.026.249.025q.037.045.058.101c.017.079.011.153-.046.22a.1.1 0 0 1-.105-.002");
}

.j91zh3b7l {
  fill: var(--svg-color--053060, #053060);
  d: path("M30.08 26.03c.043-.141.161-.188.287-.2c.773-.064 1.548-.095 2.323-.009c.147.017.209.114.306.183c.05.208.098.416.085.631a.3.3 0 0 1-.058.117a.2.2 0 0 1-.124.041c-.089-.005-.17-.041-.25-.073c-.691-.252-1.384-.275-2.079-.015a.7.7 0 0 1-.338.072c-.121-.012-.085-.146-.148-.2l.001.002c-.088-.182-.049-.364-.005-.549");
}

.jaomd_1iy {
  fill: var(--svg-color--318a3b, #318a3b);
  d: path("M37.24 31.3c0-.077-.029-.13-.106-.153c.077-.105.164-.188.341-.139a.53.53 0 0 1-.235.292");
}

.jbp9q88sd {
  fill: var(--svg-color--137418, #137418);
  d: path("M35.748 35.33q.003-.038.002-.073l.403.085c-.026.076-.102.062-.157.082a.3.3 0 0 1-.078-.023q-.084-.037-.17-.071");
}

.jf0xnkshr {
  fill: var(--svg-color--1f3762, #1f3762);
  d: path("M31.984 33.3c.02-.111.043-.221.184-.239c.064.053.216.062.146.191c-.075.137-.211.079-.33.048");
}

.jn-0nfbid {
  fill: var(--svg-color--c21024, #c21024);
  d: path("M33.917 36.995c.3-.143.472.282.763.172c.036.123.197.181.17.334q-.156.278-.418.091c-.194-.089-.338-.241-.494-.384c-.033-.047-.068-.095-.031-.156q-.013-.03.01-.057");
}

.jn2d19bso {
  fill: var(--svg-color--e4a109, #e4a109);
  d: path("M32.667 35.994c-.026.131.066.286-.077.396l-.02-.322z");
}

.jnrn9kbku {
  fill: var(--svg-color--03863d, #03863d);
  d: path("m35.574 30l.017-.065c.093-.028.066-.127.104-.187c.088-.006.091.057.095.118c.013.139.066.272.041.415c-.006.073-.032.146-.035.156c-.007-.038.055-.129.048-.229a.5.5 0 0 1 .05-.111c.072-.048.111-.215.238-.064c-.02.418-.081.824-.29 1.196a.105.105 0 0 1-.126-.021c-.206-.385-.343-.775-.142-1.208");
}

.jp8l0q4gg {
  fill: var(--svg-color--068033, #068033);
  d: path("M27.27 30.32c.132-.047.266-.093.42-.146v.314l-.013.009c-.074.111-.064.269-.195.352a.4.4 0 0 1-.107.053a.5.5 0 0 1-.3-.009c-.155-.078-.089-.202-.063-.315c.015-.106.094-.174.147-.259q.055-.033.111.001");
}

.jpjftmfng {
  fill: var(--svg-color--2c842f, #2c842f);
  d: path("m36.914 34.24l.09.078c.095-.028.202-.099.24.069c-.163.027-.33.06-.494.088q-.005-.075-.007-.146c.03-.078.08-.125.171-.089");
}

.jrbqsebyd {
  fill: var(--svg-color--e8ede9, #e8ede9);
  d: path("m27.833 35.907l-.153.002c-.117-.045-.19-.139-.256-.24a.08.08 0 0 0 .005-.076q.201-.032.398-.06c.152.013.2.12.192.246c-.006.1-.062.176-.186.128");
}

.jwgni_but {
  fill: var(--svg-color--5e5e5e, #5e5e5e);
  d: path("M31.34 34.918c.12-.021.199.141.329.075c-.175.27-.225-.025-.329-.075");
}

.jzd844bmp {
  fill: var(--svg-color--142840, #142840);
  d: path("M28.417 27.823c-.007-.125-.061-.13-.141-.055c-.079.073-.154.149-.272.146l-.02-.05c.002-.066.08-.127.019-.198a.82.82 0 0 1 .531-.249c-.109.117.114.325-.117.406");
}

.k1i7ntb-h {
  fill: var(--svg-color--70933d, #70933d);
  d: path("m35.18 31.16l-.256-.074c.065-.139-.198-.194-.088-.346c.153-.037.179.1.246.18l.089.067q.067.084.009.173");
}

.k5kz1bbzq {
  fill: var(--svg-color--d6471b, #d6471b);
  d: path("M29.08 36.403c.075-.206.279-.291.408-.175c.139.126-.042.298-.143.411c-.084.093-.218.118-.346.111c-.065-.138-.008-.245.081-.347");
}

.k5z_94b-s {
  fill: var(--svg-color--108134, #108134);
  d: path("m27.589 31.33l-.007.091a1 1 0 0 0-.336.185a.23.23 0 0 1-.175.004a.27.27 0 0 1-.12-.134c-.037-.173.061-.314.094-.472c.089-.129.259-.089.37-.172l.002-.003c.187-.019.173.13.205.24q0 .062-.026.118q-.005.072-.007.143");
}

.k8dwd8avu {
  fill: var(--svg-color--7d0a17, #7d0a17);
  d: path("m36.34 36.09l-.007.062c-.063.093-.089.244-.263.174c.071-.1.141-.204.27-.236");
}

.k8qlllb4h {
  fill: var(--svg-color--580711, #580711);
  d: path("M26.918 36.15c-.086.016-.19-.019-.24.094c-.144-.156-.018-.245.082-.34c-.024.131.103.165.158.246");
}

.kbw35nbug {
  fill: var(--svg-color--15863c, #15863c);
  d: path("M25.822 31.486c-.018-.255-.124-.511.059-.771l.398.427c-.033.18-.05.365-.277.415c-.07.005-.135-.012-.18-.071");
}

.kdu15blfk {
  fill: var(--svg-color--b42e3c, #b42e3c);
  d: path("M30.504 37.24c-.124.055-.247.105-.377.164c-.104-.29-.128-.525.259-.571c.104-.089.161-.001.223.062q.117.224-.105.345");
}

.kjldfwbgm {
  fill: var(--svg-color--6d7277, #6d7277);
  d: path("m31.747 33.983l.019-.25c.048.124.113.221.271.172c-.077.101-.179.112-.29.078");
}

.kjo930nae {
  fill: var(--svg-color--dde3ca, #dde3ca);
  d: path("M36.995 31.905c-.081.047-.145.146-.263.091c.147-.118.146-.358.346-.433q.04.048.076.095c.068.157-.05.199-.159.247");
}

.kklesxblf {
  fill: var(--svg-color--10243c, #10243c);
  d: path("M32.584 26.995c.179.009.326-.029.329-.248h.09c.015.122-.031.228-.085.333c-.116-.011-.246.04-.334-.085");
}

.ko55yxj_a {
  fill: var(--svg-color--a3941f, #a3941f);
  d: path("M34.07 26.655a2 2 0 0 0 .109-.084a.08.08 0 0 1 .056.021q0 .036.018.071c.062.085.041.147-.048.194a.14.14 0 0 1-.112-.026z");
}

.kt9dtutxd {
  fill: var(--svg-color--99881b, #99881b);
  d: path("M30.08 29.741c-.181-.002-.275-.081-.244-.271z");
}

.kxgdms20o {
  fill: var(--svg-color--e5a707, #e5a707);
  d: path("M29.991 36.17q.013-.038.021-.081c.084.017.128.084.167.149l-.1.246c-.134-.077-.056-.21-.088-.314");
}

.kxy05tb3t {
  fill: var(--svg-color--dc6c13, #dc6c13);
  d: path("M30.18 36.23c.153.087.378-.12.459.153c-.157.027-.357.061-.559.093c-.062-.12-.015-.196.1-.246");
}

.l_vn41byo {
  fill: var(--svg-color--0f2440, #0f2440);
  d: path("M30.501 26.995c.107-.129.251-.172.413-.163q.003.04.002.084q-.206.043-.415.079");
}

.l-k1ljb-o {
  fill: var(--svg-color--408a41, #408a41);
  d: path("M26.923 31.24c.021.078-.042.185.072.234l.095.078c-.01.097-.08.146-.146.205a.09.09 0 0 1-.093-.009c.008-.104-.053-.173-.12-.237c.137-.039.067-.223.192-.271");
}

.l0gxh6l2g {
  fill: var(--svg-color--391f3c, #391f3c);
  d: path("M31.08 33c-.006-.09.114-.168.023-.265c-.07-.041-.063-.091-.02-.146l.165-.002v.498c-.111.01-.093.132-.157.182c-.09-.085-.067-.176-.011-.267");
}

.l1f2wnhzr {
  fill: var(--svg-color--cfdbbf, #cfdbbf);
  d: path("M37.24 33.489c-.073.054-.144.115-.244.102c-.07.017-.104-.021-.117-.086c.01-.171.155-.197.274-.254c.095-.041.184-.154.295-.07c.086.063.014.146-.023.216c-.029.094-.131.044-.185.092");
}

.l3a-fxb9z {
  fill: var(--svg-color--dae8da, #dae8da);
  d: path("M27.08 31.813c.081-.052.167-.07.251-.006l-.151.259c-.147-.038-.106-.151-.1-.253");
}

.lad4txbqk {
  fill: var(--svg-color--eaf1ea, #eaf1ea);
  d: path("M26.941 31.735c-.027-.125.013-.193.148-.183l.164.024l-.016.009c.05.14-.067.151-.144.199c-.058.012-.113.003-.152-.049");
}

.ldx1j6tus {
  fill: var(--svg-color--6aa56e, #6aa56e);
  d: path("m28.342 34.985l-.174.091c-.033.058-.066.113-.148.076c.012-.11-.108-.255.082-.318c.031.128.197.043.24.151");
}

.ln4do8qgn {
  fill: var(--svg-color--0b6c0e, #0b6c0e);
  d: path("m36.832 33l-.58.488c-.118-.137.023-.229-.001-.331h-.002c.07-.124.188-.218.24-.355a.73.73 0 0 1 .345-.146l.172.011c.09-.052.141.005.188.07q.014.06-.009.113c-.099.096-.196.191-.353.15");
}

.lqchn_73n {
  fill: var(--svg-color--fbfafa, #fbfafa);
  d: path("M33.569 32.24c-.318.383-.797.619-.953 1.15c-.075.253-.325.194-.529.11a.16.16 0 0 1-.115-.106c.003-.019.003-.034.003-.053a.3.3 0 0 1 .074-.079c.11-.056.079-.146.056-.231c-.022-.125.021-.234.068-.344c.092-.216.022-.449.083-.668c.05-.152.164-.242.311-.299c.208-.003.104.188.167.273v.514c.284-.261.521-.479.76-.696c.223.069.126.223.095.358c-.009.023-.015.05-.02.071");
}

.lqd0s51mx {
  fill: var(--svg-color--eceee2, #eceee2);
  d: path("m35.741 35.572l.086.011q-.115.085-.232.167l-.257-.104a.1.1 0 0 1 .004-.066c.133-.125.265-.082.399-.008");
}

.lqnz3bbiu {
  fill: var(--svg-color--066e13, #066e13);
  d: path("M27.757 29.26c.182.004.281.143.407.239c-.178.078-.201.281-.328.401c-.184.137-.508.027-.59.337c-.181.021-.201-.091-.188-.229c.077-.138.159-.272.137-.448c-.012-.094-.041-.226.131-.228q.027.034.015.079c.307.277.307.277.416-.151");
}

.ly9_xca6k {
  fill: var(--svg-color--0c6f15, #0c6f15);
  d: path("M27.05 34.834c.157-.003.314-.007.455-.089c.063.031.079.08.059.145l-.259.037c-.098.007-.191-.002-.255-.093");
}

.m244qkbyw {
  fill: var(--svg-color--c9880d, #c9880d);
  d: path("M33.06 29.911q-.047-.006-.089-.009a.8.8 0 0 1 .267-.349c.002.036.007.068.009.104z");
}

.m38ptk52y {
  fill: var(--svg-color--126d0e, #126d0e);
  d: path("M35.835 31.25c0-.436.219-.828.25-1.257c-.047-.142.055-.206.148-.271a.11.11 0 0 1 .106.019l-.005.013c.025.022.046.05.065.076c.016.218-.219.37-.154.598c.092.09.035.181.006.271c-.118.19-.15.434-.361.564c-.018-.003-.037-.01-.055-.013");
}

.m3f1kjb_a {
  fill: var(--svg-color--017119, #017119);
  d: path("m27.609 31.745l-.041-.078h.391c-.131.12-.246.059-.35.078");
}

.m3qm09bpb {
  fill: var(--svg-color--01873e, #01873e);
  d: path("M35.25 35.41h-.558c.231-.288.521-.413.745-.617c.003-.003-.009-.029-.017-.032q-.04-.014-.08-.018l.154-.25q.088 0 .171.002c.179-.129.407-.14.59-.253l-.003.002c.12-.238.345-.293.579-.335l.088.008l.073.078c-.028.07-.094.073-.155.084c-.076.186-.277.163-.415.248c-.116.08-.127.163-.005.248c-.287.174-.664.22-.825.572c-.064.107-.181.09-.275.119l.008.014a1 1 0 0 1 .47-.034c.081.036.17.065.122.186a.5.5 0 0 1-.263.087c-.143.003-.29-.002-.404-.109");
}

.mbgct9b1n {
  fill: var(--svg-color--09325f, #09325f);
  d: path("m32.16 26.921l.258-.006a.26.26 0 0 1 .242.021c.082.05.191.057.258.144q.068.047.004.1c-.29.017-.637.211-.762-.259");
}

.mbu2x9h4b {
  fill: var(--svg-color--0b3261, #0b3261);
  d: path("m30.905 26.653l.009.179c-.131.07-.282.089-.413.163q-.12.002-.246.002c-.062-.082-.076-.168-.001-.252q.08-.04.164-.079c.162-.003.326-.011.487-.013");
}

.mh0k2dbnc {
  fill: var(--svg-color--329046, #329046);
  d: path("M36.34 31.409c-.044-.232.043-.411.24-.539q.015-.103.087-.026q0 .157.004.316a.6.6 0 0 1-.255.249z");
}

.mi-8zoies {
  fill: var(--svg-color--f0efed, #f0efed);
  d: path("M31.22 30.758q.098-.047.195-.097c.045-.041.086-.089.141-.122l.078-.054c.066-.05.125-.113.214-.119c.128.012.178.105.219.206c-.066.143.046.269.033.407a.17.17 0 0 1-.079.075c-.184.052-.391-.098-.561.068c-.217.047-.25-.098-.267-.259q.001-.055.027-.105");
}

.mol7zdbsj {
  fill: var(--svg-color--771722, #771722);
  d: path("m34.31 37.664l.199-.168c.118.195.233.048.352-.004q.022 0 .048-.004c-.079.221.095.153.193.171c-.262.15-.528.137-.792.005");
}

.ms_01bbxd {
  fill: var(--svg-color--ccae0e, #ccae0e);
  d: path("m31.438 26.4l-.012-.399c.133.13.095.264.012.399");
}

.ms3toqbgr {
  fill: var(--svg-color--cd1126, #cd1126);
  d: path("M29.11 34.32c-.102-.073-.124-.176-.115-.29c-.073-.586-.015-1.173-.034-1.761a.2.2 0 0 1 .05-.139a.47.47 0 0 1 .501.004c.218.331.021.72.149 1.062c.13.25.159.567.454.711a.56.56 0 0 0 .524.011c.126-.054.191-.222.361-.189a.24.24 0 0 1 .081.111c.024.314.135.639-.094.93c-.438.012-.881.051-1.318-.023c-.106.022-.177-.047-.253-.098c-.08-.131-.197-.225-.306-.329");
}

.mu9r35btu {
  fill: var(--svg-color--0c8338, #0c8338);
  d: path("M27.685 30.483c.084-.08.163-.17.256-.238c.08-.058.15-.043.133.083c-.003.178.083.138.177.073c.07-.057.14-.112.214-.176c.054.113.039.196-.031.271c-.136.506-.298.59-.759.398a.33.33 0 0 1-.07-.313a.2.2 0 0 1 .08-.098");
}

.mui9l5-mg {
  fill: var(--svg-color--87b688, #87b688);
  d: path("m27.506 31.658l-.082.009a.25.25 0 0 1-.142-.049q-.014-.018-.028-.041c.012-.252.172-.202.328-.157c-.03.079-.125.136-.076.238");
}

.mwkku3bjm {
  fill: var(--svg-color--480b12, #480b12);
  d: path("M27.16 36.834c.024-.19-.203-.202-.247-.345c.085-.073.17-.055.255 0c.102.094.17.207.165.352z");
}

.mxe3os-yu {
  fill: var(--svg-color--0a751f, #0a751f);
  d: path("M27.432 32.581c.067-.098.137-.194.242-.345c.049.258-.242.747.416.506c-.271.022-.422.238-.646.17c-.125-.107-.12-.218-.012-.331");
}

.mzhvzqb3o {
  fill: var(--svg-color--00721b, #00721b);
  d: path("M26.21 33.19c0-.128.206.021.179-.149c-.011-.065-.329-.039-.061-.167c.12-.058.197.035.19.18c-.003.063.031.126.052.209c-.136-.015-.255.002-.36-.073");
}

.n_cb1iblp {
  fill: var(--svg-color--fbfbfb, #fbfbfb);
  d: path("m30.989 34.741l.019-.987c.077-.052.141-.013.205.027c.103.081.037.222.12.306c.063.044.126.037.19.006c.067-.046.12-.117.203-.145c.081-.016.161-.029.24-.058q.05-.012.095.021c.017.281.109.564-.048.836l-.344.246c-.141.109-.223-.037-.329-.075c-.088-.13-.227-.08-.347-.094q-.033-.026-.025-.056q.013-.026.021-.027");
}

.n21_qcb1x {
  fill: var(--svg-color--298431, #298431);
  d: path("M35.15 33.748c-.168-.003-.116.194-.224.244c-.019-.227.095-.474-.109-.669c-.102.033.002.197-.136.211c-.06-.149-.03-.297-.002-.445c.061-.078.138-.082.222-.053a.43.43 0 0 1 .156.183c.08.136.104.289.138.44q.013.064-.045.089");
}

.n7p52ub7s {
  fill: var(--svg-color--12263e, #12263e);
  d: path("M33.09 26.321c-.035.143.05.308-.093.426q0-.369-.003-.74c.176.062.068.208.096.314");
}

.n8ub_3pmq {
  fill: var(--svg-color--c01023, #c01023);
  d: path("M27.17 36.489h-.255l-.162-.158l-.076-.084c.006-.229.144-.104.24-.094q.125.17.253.336");
}

.ndjrrhjda {
  fill: var(--svg-color--c9a709, #c9a709);
  d: path("M30.667 30.58c.153.059.207.203.277.332l-.021.012c-.08.033-.163.017-.247.017a.34.34 0 0 1-.191-.167a.17.17 0 0 1-.007-.102a.23.23 0 0 1 .098-.12q.055-.016.091.028");
}

.ngyq4ss7w {
  fill: var(--svg-color--132439, #132439);
  d: path("m30.25 26.745l.001.252c-.198-.081-.168-.256-.169-.417z");
}

.nh4_rd0gk {
  fill: var(--svg-color--d22e20, #d22e20);
  d: path("M29.08 36.403c.025.129-.026.238-.08.348c-.085.075-.168.176-.294.096c-.015-.008.027-.112.043-.172c-.051-.102.007-.151.091-.184c.073-.052.117-.181.24-.088");
}

.ni5guwb0q {
  fill: var(--svg-color--04863b, #04863b);
  d: path("M35.996 32.33c.004-.288.207-.539.174-.834c.054-.081.11-.141.194-.035c.096.281-.157.465-.198.709q-.043.122-.083.244q-.044-.04-.087-.084");
}

.nnvzshixl {
  fill: var(--svg-color--d9e7d9, #d9e7d9);
  d: path("M27.09 30.333a.1.1 0 0 0 .074-.002a.3.3 0 0 1-.093.234c-.091.057-.108-.029-.147-.073c-.112-.228.05-.168.166-.159");
}

.np3e_pbxn {
  fill: var(--svg-color--2e1108, #2e1108);
  d: path("M30.844 36.583a.2.2 0 0 0 .003.069l-.184.074q-.015.074-.07.021c-.037-.083-.118-.086-.192-.104c.137-.09.29-.07.443-.06");
}

.ns5y8l9bc {
  fill: var(--svg-color--103903, #103903);
  d: path("M32.09 36.646c-.138.035-.261.144-.417.089c-.262-.154-.564.106-.823-.082q-.051-.022-.035-.043q.016-.027.032-.026a7 7 0 0 1 1.238-.008q.037.022.027.046q-.01.025-.022.024");
}

.nx38k027i {
  fill: var(--svg-color--c91226, #c91226);
  d: path("M26.995 35.639c-.03.132-.124.209-.235.269c-.084.1-.05.199-.003.301c.025.053.031.107 0 .161c-.076.068-.151.139-.243.024c-.315-.275-.331-.712-.555-1.041c-.078-.115.031-.165.133-.145c.07.012.141.052.156-.048c.078-.54.261-.111.352-.022c.154.144.265.331.395.501");
}

.offl7bbly {
  fill: var(--svg-color--1f6e0c, #1f6e0c);
  d: path("M35.24 33.427c-.127-.047-.026-.225-.154-.273l.008-.138c.135-.07.157.038.196.124c.009.063.112.115.023.192q-.034.047-.073.095");
}

.om-a9lk2v {
  fill: var(--svg-color--098b43, #098b43);
  d: path("M36.584 32.25c.15-.025.098-.169.148-.25c.088-.042.16-.112.259-.133c.09.003.143.056.184.126l.005-.009c.047.1-.048.13-.089.188l-.106.158c-.146.132-.317.242-.43.411a1 1 0 0 1-.141.091l-.246.002v-.089c.135-.169.263-.342.416-.495");
}

.oq3eq2bll {
  fill: var(--svg-color--6b933c, #6b933c);
  d: path("M37.24 34.39c-.064-.077-.158-.055-.24-.069a.3.3 0 0 1-.002-.083h.521l.012.063q-.145.043-.291.089");
}

.oqxy3bb3h {
  fill: var(--svg-color--168b41, #168b41);
  d: path("M36.752 31.427c-.088.072-.04.293-.253.229c-.083-.064-.13-.141-.112-.249a.54.54 0 0 1 .23-.252a.12.12 0 0 1 .107.006c.008.09.019.176.028.266");
}

.ous-fqbfs {
  fill: var(--svg-color--0f6f15, #0f6f15);
  d: path("M29.17 35.659c-.208-.021-.158-.174-.16-.302c.119.066.081.212.16.302");
}

.ov6981bcd {
  fill: var(--svg-color--c2a812, #c2a812);
  d: path("M33.3 26.944c-.079-.129-.056-.256-.031-.416c.101.159.043.287.031.416");
}

.ovpzd3x_p {
  fill: var(--svg-color--062f5f, #062f5f);
  d: path("M28.417 27.823c-.123.198-.321.279-.532.339c-.44.126-.894.219-1.313.414c-.083 0-.12-.029-.079-.114c-.004-.084.186-.244-.09-.222c-.11.011-.22.003-.421.003c.407-.366.84-.498 1.274-.631c.152-.005.291.022.395.156c.094.123.212.166.353.068c.101-.043.176-.132.278-.162c.135-.041.219-.019.135.149");
}

.oysgywcay {
  fill: var(--svg-color--127d2f, #127d2f);
  d: path("m26.941 31.735l.143.026q.043.031.063.076c.041.07-.041.16.03.229a.58.58 0 0 0 .048.391l-.021.026l-.143.292l-.228.138a.44.44 0 0 0-.085-.396a.33.33 0 0 1-.076-.271v-.087l.178-.41q.044-.009.091-.014");
}

.p_e7lzcsr {
  fill: var(--svg-color--016a0d, #016a0d);
  d: path("m35.754 30.31l.162-.155c-.035.17-.068.339-.11.54c-.087-.148-.046-.268-.052-.385");
}

.p04z3abwk {
  fill: var(--svg-color--324c4d, #324c4d);
  d: path("M28.672 26.923c.044.11.131.251-.053.292c-.165.038-.197-.083-.165-.229c.007-.046-.023-.1-.035-.151c.126-.092.193-.012.253.088");
}

.p1lciv31g {
  fill: var(--svg-color--7b9b49, #7b9b49);
  d: path("M37.09 32.17a5 5 0 0 0 .089-.188c.122.032.186-.097.318-.113c-.052.233-.213.289-.407.301");
}

.p3m6o55dy {
  fill: var(--svg-color--e1910c, #e1910c);
  d: path("M34.26 36.653c-.205.121-.168-.078-.21-.164c-.021-.044.018-.077.061-.073c.17.009.064.181.145.245z");
}

.p3qnyw91p {
  fill: var(--svg-color--7d7b7b, #7d7b7b);
  d: path("M31.17 32.33c-.013.129.06.17.173.17l-.089.089a.22.22 0 0 1-.173.041c-.179-.062-.22-.24-.323-.367c-.091-.166-.226-.325-.099-.532c.062-.033.121-.039.173.021l.19.318c.096.062.117.165.148.26");
}

.p7mk8nyew {
  fill: var(--svg-color--dde1c6, #dde1c6);
  d: path("m36.34 29.663l.008-.086c.062.033.041.063-.008.086");
}

.pa6lxsbms {
  fill: var(--svg-color--006b0f, #006b0f);
  d: path("m36.828 33.909l-.579.335c-.011-.062-.141-.128-.081-.149c.215-.073.395-.287.66-.186");
}

.pqnngwnwe {
  fill: var(--svg-color--364a5f, #364a5f);
  d: path("m34.07 26.655l-.322-.231c.163-.006.337-.047.432.147c-.015.057-.052.082-.11.084");
}

.ps_m-qbkv {
  fill: var(--svg-color--158030, #158030);
  d: path("M34.01 35.988a6 6 0 0 1-.093-.247h-.002c.257-.161.564-.143.838-.243c.178-.032.355-.05.531.015a.2.2 0 0 1 .083.085c.084.204-.229.161-.207.329c-.068.216-.258.169-.412.172c-.162.006-.33-.027-.495-.034q-.122-.037-.243-.077");
}

.pv8xtub5m {
  fill: var(--svg-color--dfe4de, #dfe4de);
  d: path("M27.924 36.32c-.087-.132-.217-.242-.244-.41c.046-.048.104-.056.164-.045c.113.031.221.088.341.1c.124.041.314-.023.327.197c-.14.088-.28.172-.418.26c-.1.037-.128-.043-.17-.102");
}

.pw5cswn1y {
  fill: var(--svg-color--eef4ee, #eef4ee);
  d: path("M26.921 34.33q-.053-.016-.105-.035c-.081-.04-.161-.068-.253-.044l-.141-.231l.584-.022q.164.066.115.233c-.045.077-.146.039-.2.099");
}

.pwzksgbti {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M37 54h17c6.627 0 10-4.925 10-11v-6H37z");
}

.q3dr23i2i {
  fill: var(--svg-color--098032, #098032);
  d: path("M26.67 33.495c-.148-.181-.387-.016-.539-.131c-.112-.084-.479-.018-.232-.373c.059-.086-.102-.316-.161-.486c.133-.09.243-.008.354.014c.111 0 .219.022.317.077c.173.085.351.159.495.292a.6.6 0 0 1 .196.386c0 .14-.006.273-.149.349q-.194.051-.281-.128");
}

.q4tvyygek {
  fill: var(--svg-color--c02233, #c02233);
  d: path("M32.32 31.98c-.011.259.096.526-.061.774c-.06.033-.12.044-.184.013c-.098-.147-.114-.319-.15-.484a.3.3 0 0 1 .029-.126c.089-.127.178-.255.366-.177");
}

.q52kyabba {
  fill: var(--svg-color--6b4146, #6b4146);
  d: path("m30.989 34.741l.005.083c-.44-.034-.89.093-1.323-.079q.66 0 1.318-.004");
}

.q576ofbvc {
  fill: var(--svg-color--ca1126, #ca1126);
  d: path("M27.92 36.586c-.151.381.057.615.332.823a.3.3 0 0 1 .082.094c.049.27-.107.206-.255.156c-.401-.135-.538-.506-.743-.818a2 2 0 0 1-.223-.299c-.089-.113-.19-.214-.277-.329c-.072-.088-.155-.169-.122-.299c.05-.137.17-.201.281-.275l.068-.079c.122-.029.242-.053.355.021c.111.083.203.185.29.294c.078.144.207.255.265.41c.043.111-.033.2-.053.301");
}

.q6cbv9w0w {
  fill: var(--svg-color--aacaaa, #aacaaa);
  d: path("M27.16 33.824c-.068.046-.062.159-.164.171c-.063-.159-.024-.25.164-.237a.08.08 0 0 0 0 .066");
}

.q7sbiob4m {
  fill: var(--svg-color--d49c06, #d49c06);
  d: path("m33.1 29.01l-.103-.015c-.018-.162.079-.24.211-.311c.059.158.014.255-.108.326");
}

.q8t8ivbou {
  fill: var(--svg-color--998715, #998715);
  d: path("m30.08 29.02l.077-.107c.014.128.155.225.083.397c-.107-.076-.133-.183-.16-.29");
}

.qe2sl7f0h {
  fill: var(--svg-color--348335, #348335);
  d: path("m27.25 33.831l.009.25c-.074.035-.012.222-.176.159l-.074-.248l-.005.003c.066-.044.003-.214.164-.171z");
}

.qfqkr77ru {
  fill: var(--svg-color--0c7f32, #0c7f32);
  d: path("M27.506 34.673v.072c-.121.184-.289.123-.455.089c-.066-.187-.481-.13-.326-.472a.26.26 0 0 1 .159-.109a.5.5 0 0 1 .103-.011c.158.007.268.112.392.186c.09.056.065.175.127.245");
}

.qr9bhtvsx {
  fill: var(--svg-color--8a8429, #8a8429);
  d: path("M33.675 26.979c-.006-.121-.014-.251.141-.284c.089-.019.089.073.102.134c.051.037.054.082.009.125c-.078.068-.167.037-.252.025");
}

.qs3-5rbrn {
  fill: var(--svg-color--88a050, #88a050);
  d: path("M35.765 29.507c.004-.097.03-.18.133-.226a.45.45 0 0 1-.057.385c-.073-.029-.03-.115-.076-.159");
}

.quauwu6ry {
  fill: var(--svg-color--047c2b, #047c2b);
  d: path("M28.09 33.898c-.126.267-.346.025-.507.094c-.13 0-.246-.054-.363-.1a.3.3 0 0 1-.09-.068a.4.4 0 0 1-.044-.105c-.021-.151.016-.306-.031-.455a.36.36 0 0 1 .183-.224a.4.4 0 0 1 .114-.021c.132.015.262.041.389.09c.122.063.151.196.229.292c.078.062.226.029.244.172c.029.135-.104.208-.124.325");
}

.qv9u9j1fp {
  fill: var(--svg-color--012c60, #012c60);
  d: path("M32.584 26.995c-.055-.023-.108-.053-.166-.08c-.07-.104-.286-.238.055-.251h.281q.08.04.159.083c.059.303-.102.316-.329.248");
}

.qvucqnv_q {
  fill: var(--svg-color--989898, #989898);
  d: path("M30.979 28.497a.1.1 0 0 0 .02-.08q.547 0 1.092.002a.15.15 0 0 0 .021.072l-.033.012c-.356.176-.71.185-1.062-.006l-.019.014z");
}

.r_h3nkgib {
  fill: var(--svg-color--057118, #057118);
  d: path("M28.02 33.24c-.114.052-.097.157-.105.252l-.163-.331q.072-.043.146-.083q.059.082.122.162");
}

.r_zgk4bgl {
  fill: var(--svg-color--2e8837, #2e8837);
  d: path("M36.995 31.905q.082-.124.159-.247c.075-.041.185-.149.155.054c-.015.098-.087.187-.135.277q-.089-.04-.179-.084");
}

.r-3kyjjbc {
  fill: var(--svg-color--018a44, #018a44);
  d: path("M35.491 34.493c.36-.386.364-.969.76-1.333c.06.1.122.122.221.031c.098-.089.192-.192.333-.224c.114.015.156.105.206.188h-.005c.027.153-.145.224-.151.362c-.063.174.057-.011.06.028q.035-.018.069-.033c.091-.039.182-.079.285-.063c.089.039.13.093.062.186q-.205.126-.409.255q-.016.021-.03.045a.3.3 0 0 1-.108.027c-.182.063-.405.05-.509.263a.2.2 0 0 1-.074.077c-.201.042-.371.152-.553.238c-.059.008-.113-.002-.157-.047");
}

.r-l-fpmfg {
  fill: var(--svg-color--046b0d, #046b0d);
  d: path("M36.422 30.576c-.063.228-.136.447-.339.594l.178-.505z");
}

.r3u4__vgv {
  fill: var(--svg-color--5e0812, #5e0812);
  d: path("M34.906 37.488q-.026.001-.05.004c-.041-.116-.218-.161-.177-.325l.256.24z");
}

.rgypmzbcu {
  fill: var(--svg-color--cb1226, #cb1226);
  d: path("M33.569 32.24c0 .331.017.662-.003.991c-.021.377-.203.666-.565.792c-.335.119-.621.009-.844-.269c-.098-.06-.146-.141-.095-.257c.301-.021.464-.18.619-.446c.206-.345.461-.686.888-.811");
}

.rj833nb5x {
  fill: var(--svg-color--faf8f8, #faf8f8);
  d: path("m30.585 31.658l.084.012a.3.3 0 0 0 .002.077c-.03.192.091.336.166.492c.098.143.012.393.265.441c.138.089.063.202.037.312c-.058.111-.298.188-.07.356c.002.113-.1.153-.16.222c-.177.005-.353-.042-.396-.22c-.129-.523-.61-.734-.921-1.094c-.041-.173-.067-.342-.013-.514l.851.766v-.932c.088-.042.111.041.155.082");
}

.rld3kzkak {
  fill: var(--svg-color--498b35, #498b35);
  d: path("M35.01 29.01c.091.161.012.281-.1.392c-.088.058-.116-.037-.17-.065c-.081-.195-.096-.35.19-.334q.05-.089.08.007");
}

.rodcyu01h {
  fill: var(--svg-color--a2c29e, #a2c29e);
  d: path("m27.01 29.991l.05.014c.038.098.064.206.189.229q.015.038.019.081q-.05.007-.098.016q-.038.04-.074.002L27 30.182q.004-.098.01-.191");
}

.rrtnijb0p {
  fill: var(--svg-color--87101d, #87101d);
  d: path("M34.25 29.1q-.04.01-.08.016a.63.63 0 0 1 .337-.367c-.018.167-.153.246-.257.351");
}

.ruxtncbdw {
  fill: var(--svg-color--e1e1e1, #e1e1e1);
  d: path("m31.17 32.33l-.147-.261c.144-.032.149-.242.317-.243c.111.087.088-.093.163-.083c.165.354-.253.374-.333.587");
}

.rwhno3bam {
  fill: var(--svg-color--0b8135, #0b8135);
  d: path("M27.755 33.16a.7.7 0 0 1-.423-.087a.1.1 0 0 1-.023-.068q.005-.036.009-.037a.3.3 0 0 1 .132-.109c.119-.027.232-.075.311-.066c.1.019.055-.072.055-.017c0 0-.011 0-.025.005c-.121.02-.199.008-.2-.156c-.002-.285-.134.121-.174-.026a.25.25 0 0 1-.141-.187c.008-.261.143-.431.376-.529a.13.13 0 0 1 .115.035c.005.343.226.327.425.261c.156.13-.327.465.199.438c.037-.002-.013.12-.046.178c-.094.178-.292.192-.443.283a.18.18 0 0 1-.147.082");
}

.s83r-r71n {
  fill: var(--svg-color--036605, #036605);
  d: path("M26.673 32.25c.103.068.078.174.076.271a.2.2 0 0 1-.063-.011l-.29-.141c.105-.044.189-.08.277-.119");
}

.s8ym8nb7u {
  fill: var(--svg-color--24771a, #24771a);
  d: path("m35.765 29.507l.076.159l-.024.164l-.063-.007q-.03-.037-.06-.07z");
}

.sc6y04bri {
  fill: var(--svg-color--cfad0c, #cfad0c);
  d: path("M30.518 30.576q-.005.043-.012.085c-.056-.008-.104-.025-.102-.096z");
}

.sdqa_hbvl {
  fill: var(--svg-color--df850e, #df850e);
  d: path("M34.25 36.661c.091-.011.107-.213.216-.114c.073.068.079.25-.011.294c-.098.047-.205-.044-.2-.188z");
}

.shv5b-b4z {
  fill: var(--svg-color--eef4ee, #eef4ee);
  d: path("m27.26 34.17l.254-.094l-.006.597c-.124-.002-.06-.158-.15-.186c-.107-.082-.15-.184-.098-.317");
}

.snq8c9ydp {
  fill: var(--svg-color--73a808, #73a808);
  d: path("M30.25 37.524c.068.047.174.047.18.162c-.072.07-.154.068-.22.005c-.053-.056-.041-.127.04-.167");
}

.sopzmt9hv {
  fill: var(--svg-color--052f62, #052f62);
  d: path("m33.645 29.775l.017 1.298l.005.012c-.111.246.036.527-.107.772c-.138.188-.313.341-.481.498c-.087.079-.183.192-.316.126c-.109-.053-.104-.182-.114-.29c-.01-.082-.01-.163-.01-.243c-.005-.434.015-.867-.013-1.299a.3.3 0 0 1 .07-.238c.257-.129.466-.318.661-.528c.092-.039.153-.169.288-.108");
}

.sr7fn6xaq {
  fill: var(--svg-color--e4eee4, #e4eee4);
  d: path("m27.85 35.08l-.095.091c-.057-.09-.173-.135-.17-.261c.136-.02.208.065.265.17");
}

.su2jtum9t {
  fill: var(--svg-color--0d6d11, #0d6d11);
  d: path("M27.25 33.831a.43.43 0 0 1 .34.161l-.075.084c-.067.086-.138.168-.265.104a.24.24 0 0 1-.063-.108a.27.27 0 0 1 .063-.241");
}

.sx3wyse7r {
  fill: var(--svg-color--d5d5d5, #d5d5d5);
  d: path("M30.828 31.753q-.079-.002-.157-.006a.23.23 0 0 1-.072-.091c-.024-.114-.093-.226.005-.338c.053 0 .113.016.157-.005c.124-.061.239-.066.316.055c.111.18-.133.151-.163.253c-.016.049-.057.089-.086.132");
}

.sz04ebcjf {
  fill: var(--svg-color--fdfdfd, #fdfdfd);
  d: path("M34.18 33.906c.003-.411-.028-.829.015-1.236c.046-.429-.1-.593-.52-.525c-.211-.325-.132-.67-.065-1.014q.024-.03.05-.058c.463.091.576-.118.535-.553c-.046-.463-.021-.935-.026-1.402q.023-.098.08-.016c0 1.455.003 2.911-.002 4.365c-.001.148.049.309-.067.439");
}

.t_eecl_wr {
  fill: var(--svg-color--8c8528, #8c8528);
  d: path("m28.753 26.822l-.011.077a.3.3 0 0 1-.07.023c-.077-.049-.146-.127-.253-.089c.102-.195.221-.028.334-.011");
}

.t_sj99vdo {
  fill: var(--svg-color--3f1217, #3f1217);
  d: path("M29.26 37.421c0-.115-.05-.186-.174-.181a6 6 0 0 0 .208-.185c.053.127.106.256-.034.366");
}

.t7vte7bed {
  fill: var(--svg-color--669647, #669647);
  d: path("m37.12 32.751l.134-.105c.06.016.146.01.157.086c.018.114-.085.144-.163.182c-.043-.027-.087-.06-.13-.088z");
}

.tbbt3ofnj {
  fill: var(--svg-color--042f63, #042f63);
  d: path("M30.3 30.422q.048.074.101.144q.037.029.076.052c.006.016.015.027.021.042q.014.03.032.061c-.027.143.012.287-.011.429a.7.7 0 0 0-.015.188q.022.129.022.26c0 .178.005.357-.004.535c-.006.135.012.309-.134.362c-.141.05-.249-.089-.349-.18a2 2 0 0 1-.465-.571l-.002-.015c.002-.474.002-.949.01-1.425c.005-.129-.056-.275.084-.377c.248.116.347.426.634.495");
}

.tbredts0m {
  fill: var(--svg-color--01741e, #01741e);
  d: path("M26 31.493c.186-.044.133-.277.279-.352q.021-.02.053-.011c.084.234-.184.6.264.695c.166.124.066.217-.039.308a.4.4 0 0 1-.397-.038a.12.12 0 0 1-.067-.038c.178-.22-.145-.361-.093-.564");
}

.tcgq7uj8p {
  fill: var(--svg-color--3f9144, #3f9144);
  d: path("m36.914 30.563l-.036.013c-.105.019-.181.13-.301.098c-.047-.06-.039-.118.003-.179l.093-.264c.118.062.209.148.235.284z");
}

.tcxguub1h {
  fill: var(--svg-color--0b8336, #0b8336);
  d: path("M34.999 29.577c.093.164.401.22.252.505a.57.57 0 0 1-.243.19a.1.1 0 0 1-.093-.038c.06-.322-.326-.337-.399-.568c.156-.052.326-.036.483-.089");
}

.tjis19bmo {
  fill: var(--svg-color--012d61, #012d61);
  d: path("M34.18 33.906c-.165.626-.525.921-1.169.909c-.333-.004-.677.096-1-.068c-.07-.263-.033-.53-.029-.796a.6.6 0 0 1 .036-.129c.034-.064.08-.106.156-.104c.813.433 1.285.144 1.301-.797c.006-.233-.028-.472.044-.703a.25.25 0 0 1 .09-.109a.5.5 0 0 1 .143-.052c.335-.044.485.082.461.439c-.036.47.026.942-.032 1.41");
}

.tk-fmqcmj {
  fill: var(--svg-color--142338, #142338);
  d: path("M28 27.914c-.138.161-.249.05-.336-.055c-.112-.132-.263-.185-.412-.247c.085-.037.172-.073.134-.197c.183.102.245.336.449.412a.2.2 0 0 1 .164.085z");
}

.tk2ldt9_j {
  fill: var(--svg-color--0b8135, #0b8135);
  d: path("m27.766 31.917l-.076-.007q-.139-.031-.117-.171c.087-.063.19-.014.311-.052c-.107.022-.187.01-.266.015a.23.23 0 0 1-.112-.017c-.081-.091-.05-.185-.003-.278a.24.24 0 0 1 .087-.078c.268-.045.529-.016.79.029c-.063.359-.16.661-.614.559");
}

.tn69im68l {
  fill: var(--svg-color--f1f0f0, #f1f0f0);
  d: path("M31.999 33.35a.1.1 0 0 1 .002.057c.081.134.029.289.068.427q-.007.038-.008.075l-.024-.006c-.162.096-.256.008-.331-.124a.7.7 0 0 1-.055-.195c-.019-.215-.078-.433-.021-.651c.029-.194-.026-.403.087-.587c.066-.06.122-.027.179.022c.111.13.125.289.132.452c.004.176.009.354-.029.53");
}

.tnbwsfb5d {
  fill: var(--svg-color--e5e5e5, #e5e5e5);
  d: path("m31.664 31.66l-.165.085c-.038.063-.022.168-.126.17c-.04.002-.053-.046-.037-.087c-.172-.229.06-.299.164-.416l.098-.005c.087.07.069.164.066.253");
}

.tog720bax {
  fill: var(--svg-color--ca1125, #ca1125);
  d: path("m36.414 35.901l-.07-.072a.42.42 0 0 1-.105-.293q0-.067.016-.127c.117-.224.23-.451.48-.559a.18.18 0 0 1 .12.026c-.026.413-.026.413.265.271c.126-.03.183.005.131.14c-.248.309-.321.703-.527 1.032c-.046.056-.102.05-.16.019c-.131-.118-.061-.304-.15-.437");
}

.topaw4f1u {
  fill: var(--svg-color--283b4f, #283b4f);
  d: path("M28.892 29.09c.166.083.108.235.11.364c.007.398.004.796.002 1.195c0 .187-.017.36.263.354c.257-.008.224-.173.24-.339c.033-.334-.094-.681.078-1c.104.08.143.188.136.316c-.056.569.063 1.144-.078 1.708a.17.17 0 0 1-.099.081c-.112-.033-.134-.135-.134-.226c.001-.262-.151-.355-.378-.388a.3.3 0 0 1-.097-.077l-.043-1.985");
}

.tqyba-tll {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M26 10H10C3.373 10 0 14.925 0 21v6h26z");
}

.trlmgccva {
  fill: var(--svg-color--6b6b6b, #6b6b6b);
  d: path("M28.993 32.18a.08.08 0 0 0-.06-.018l.002-1.095a.2.2 0 0 1 .073.012c.177.353.184.707.008 1.065q-.001.023-.023.036");
}

.u6kk8lbza {
  fill: var(--svg-color--cbad0e, #cbad0e);
  d: path("m30.758 26.26l-.019.115c-.021-.006-.061-.012-.061-.012c.009-.118-.103-.259.07-.34c.189.073.084.157.01.237");
}

.u6lvlp4ai {
  fill: var(--svg-color--177117, #177117);
  d: path("M27.08 34.24q.087-.08.176-.159l.002.089q.048.16.098.317c-.172.016-.247-.223-.435-.162c.028-.075.097-.072.159-.085");
}

.ua6b9y3vh {
  fill: var(--svg-color--018a44, #018a44);
  d: path("m36.501 32.742l.009.089a.44.44 0 0 1-.261.329c-.038-.157.075-.238.165-.331z");
}

.ucq-o_bmz {
  fill: var(--svg-color--6e9137, #6e9137);
  d: path("M35.17 31.16c.225.091.28.297.334.503l-.348-.095l.006-.137z");
}

.ufb7rgbyc {
  fill: var(--svg-color--707434, #707434);
  d: path("M31.784 25.923c.13.009.155.097.12.175c-.047.097.047.29-.153.284c-.111-.005-.083-.125-.083-.201c-.004-.107-.032-.232.116-.258");
}

.uguzfczxn {
  fill: var(--svg-color--006e13, #006e13);
  d: path("M36.17 32.17c-.025-.271.224-.476.172-.752l.036-.023c.016.006.027.01.042.018l.083.247z");
}

.uk4434bff {
  fill: var(--svg-color--2c4b13, #2c4b13);
  d: path("M32.591 36.812q-.042.014-.085.025c-.024-.008-.052-.02-.076-.027q-.08-.088-.004-.174c.109-.021.217-.035.324.013l.133.016z");
}

.ulbxc6b_n {
  fill: var(--svg-color--128339, #128339);
  d: path("m29.664 35.894l-.038.004l-.039-.009c-.074-.015-.099-.079-.134-.132c-.163.149-.162.026-.162-.096c0 0-.021-.014-.028-.011c-.011.005-.02.018-.031.029a.13.13 0 0 1-.093-.011c-.079-.055-.112-.141-.157-.214l-.059-.083q-.027-.044-.004-.094c.104-.262.242-.332.431-.063c.022.032.047.075.081.089c.332.145.332.143.25.517q.037.033.019.054q-.02.02-.036.02");
}

.unflzxbds {
  fill: var(--svg-color--ba1022, #ba1022);
  d: path("M30.593 36.747a.4.4 0 0 1 .07-.021c.131.237.505-.078.587.261c-.231-.013-.395.141-.576.248c-.019-.115.031-.248-.094-.335z");
}

.uph-t29kf {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M31.5 31.412a.43.43 0 0 0-.097-.329c.155-.328.396-.08.598-.089c-.044.225-.276.27-.403.413q-.048.044-.098.005");
}

.uscjbyb-t {
  fill: var(--svg-color--b93c21, #b93c21);
  d: path("M26.563 34.25c.004-.076-.013-.188.098-.178c.109.011.188.087.155.222l-.091.072z");
}

.v06u8qbeg {
  fill: var(--svg-color--1f242c, #1f242c);
  d: path("M36.571 28.336c-.07-.063-.185-.13.011-.169c.113-.023.252.041.334-.096c.053.037.146.07.149.111c.007.1-.091.055-.146.066c-.116.03-.272-.101-.348.088");
}

.v1c8rob_k {
  fill: var(--svg-color--dde2c8, #dde2c8);
  d: path("m35.673 35.413l.245-.018a.14.14 0 0 1 .107-.018c.072.029.141.061.161.147c-.023.054-.047.104-.12.06l-.239-.002a.09.09 0 0 1-.098.01c-.056-.048-.114-.096-.056-.179");
}

.v3--swbew {
  fill: var(--svg-color--f0f0ed, #f0f0ed);
  d: path("M34.25 36.06c.245-.161.519-.039.776-.074c.19-.026.069-.066-.006-.093q.262-.248.478.017l-.25.396c-.041.06-.065.144-.17.109z");
}

.v7x-myklw {
  fill: var(--svg-color--d85518, #d85518);
  d: path("M32.59 36.421c-.164-.061-.351.01-.508-.092c-.037-.113-.1-.228.002-.341c.188-.132.325.052.486.079c.109.082.105.188.062.304z");
}

.vadu-9eyl {
  fill: var(--svg-color--f8f8f7, #f8f8f7);
  d: path("M31.25 30.845c.091.055-.032.249.153.238c.141.048.178.148.144.285c.006.18-.197.281-.181.467c-.137.078-.155.326-.389.269a.46.46 0 0 1-.194-.342c-.016-.136.134-.203.146-.326c-.099-.073-.222-.007-.318-.067a.12.12 0 0 1-.058-.086c.019-.121.123-.164.2-.234l.104-.105a.11.11 0 0 1 .087-.03l.074-.192c.096.004.17.051.232.123");
}

.vbfn75h3y {
  fill: var(--svg-color--097824, #097824);
  d: path("M27.26 35.489c-.044-.053-.091-.103-.126-.159c-.085-.138-.35-.354.111-.281c.069.01.064-.067.059-.122c.076-.093.163-.096.259-.037l.021.017a.8.8 0 0 1 .233.261c.056.109.105.223.038.348c-.112.105-.239.162-.396.106a.8.8 0 0 1-.199-.133");
}

.vbs4ybdyb {
  fill: var(--svg-color--f4f7f4, #f4f7f4);
  d: path("M28.842 35.909q.016.075.029.149q-.115.022-.229.046c-.03-.166.051-.215.2-.195");
}

.vd0pt8b4z {
  fill: var(--svg-color--efefef, #efefef);
  d: path("m31.42 32.491l-.081.011c-.121.065-.19.017-.227-.103c-.015-.292.358-.375.358-.66c.05-.064.103-.116.193-.079l.092.005a.29.29 0 0 1 .131.276a.34.34 0 0 1-.117.18c-.068.055-.137.108-.186.181c-.037.057-.073.113-.12.163q-.02.014-.043.026");
}

.vjooj0dxm {
  fill: var(--svg-color--7d1721, #7d1721);
  d: path("M34.666 28.63c-.066-.217-.248-.129-.381-.131c-.724-.01-1.448-.008-2.174-.01q-.045-.012-.04-.04q.007-.031.019-.03q1.223-.011 2.446-.013c.159 0 .37-.014.13.224");
}

.vnti5abcq {
  fill: var(--svg-color--658620, #658620);
  d: path("m35.908 29.979l.001.177l.007.003c-.078.025.013.228-.162.155v-.49q.038-.053.063.007c.026.051.005.131.091.148");
}

.vowd7abck {
  fill: var(--svg-color--528931, #528931);
  d: path("M36.725 31.16h-.027l-.026-.001c-.094-.075-.096-.178-.087-.284a.47.47 0 0 1 .187-.304a.23.23 0 0 1 .111-.039a.2.2 0 0 1 .104.046q.014.038.025.077c-.001.156-.15.249-.176.394z");
}

.vt687uk4p {
  fill: var(--svg-color--e5dfc1, #e5dfc1);
  d: path("m30.518 30.576l.079.025l-.096.058l.005.002q-.032-.032-.017-.06q.017-.024.029-.025");
}

.vxgvyeb5d {
  fill: var(--svg-color--75aa75, #75aa75);
  d: path("m27.676 30.828l-.086.276c-.138-.041-.025-.238-.173-.276l.255-.336z");
}

.w2hpek78g {
  fill: var(--svg-color--0c6805, #0c6805);
  d: path("m37.35 34.01l-.364-.014c-.075.021-.091-.012-.073-.078l.005-.026c.131-.002.261-.009.392 0c.077.004.119.045.04.118");
}

.w35_yls4a {
  fill: var(--svg-color--f2f7f2, #f2f7f2);
  d: path("M26.323 32.663c.051-.215.291.007.363-.156q.049-.042.108-.013c.121.104.146.228.084.375l-.043.039z");
}

.w4k8-n-nx {
  fill: var(--svg-color--e6e9d5, #e6e9d5);
  d: path("M35.15 33.671a2 2 0 0 0 .098-.093c.005.095.114.2-.024.276c-.005.005-.049-.07-.076-.106a.14.14 0 0 0 .002-.077");
}

.w9p0k0b7q {
  fill: var(--svg-color--278c3f, #278c3f);
  d: path("M35.415 32.16c-.178.118-.176.238-.085.438c.199.436.19.913.145 1.481c-.054-.266-.086-.436-.12-.603c.073-.139-.054-.228-.085-.341c-.07-.146-.014-.353-.209-.441a.43.43 0 0 1-.211-.127c.019-.313.206-.483.487-.569c.061.036.123.071.078.162");
}

.wahgfab9w {
  fill: var(--svg-color--137431, #137431);
  d: path("M28.842 35.909c.181-.17-.068-.335-.003-.502q.038-.049.078-.096l.093.046c.057.1.013.25.16.302c.115.061.148.199.254.27l-.553.13c-.024-.048-.095-.085-.029-.15");
}

.wawaiccjf {
  fill: var(--svg-color--012c5f, #012c5f);
  d: path("M28 27.912c-.069-.003-.131-.015-.164-.085l.164-.161c.263.08-.029.165 0 .246");
}

.wc6qwac-t {
  fill: var(--svg-color--5e252b, #5e252b);
  d: path("M28.993 32.18q0 .922.003 1.846c-.162-.616-.048-1.243-.063-1.863q.044-.042.06.017");
}

.whcz66qsa {
  fill: var(--svg-color--616a3a, #616a3a);
  d: path("M33.675 26.979c-.087-.008-.241.084-.192-.129c.033-.146.009-.305.102-.436q.082.008.166.009c.145.054.31.079.378.251a.2.2 0 0 1-.026.168c-.048.041-.104.034-.162.023c-.126-.043-.196.034-.266.114");
}

.wqd48sb-y {
  fill: var(--svg-color--90988d, #90988d);
  d: path("M27.26 35.489c.085-.012.149.009.167.104q.03.042-.005.076c-.102-.097-.232-.1-.358-.109c.042-.082.118-.084.196-.071");
}

.wt_vf76hl {
  fill: var(--svg-color--4e060e, #4e060e);
  d: path("M36.505 36.31c-.002-.11-.065-.157-.172-.163q-.034-.026-.021-.043q.015-.02.027-.019c.076-.041.068-.118.074-.187a.4.4 0 0 1 .15.418a.3.3 0 0 0-.058-.006");
}

.wuxfuqbud {
  fill: var(--svg-color--7b161e, #7b161e);
  d: path("M30.504 37.24a.42.42 0 0 0 .063-.341l.013.004c.231.056.153.199.094.335l-.019.029z");
}

.wwu7mrbnt {
  fill: var(--svg-color--cd1226, #cd1226);
  d: path("M32.504 35.755h.083c.174.074.368-.014.54.068h.201c.227-.037.436.056.655.083c.1.022.19.062.283.096c.288.088.565.188.821.344q.174.125.322.275c.063.372-.076.633-.44.835c-.141-.014-.22-.146-.35-.179c-.259-.034-.474-.178-.703-.282V37c-.054-.179-.233-.101-.34-.171a2.1 2.1 0 0 1-.692-.165q-.066.026-.134.017c-.235-.024-.467.025-.698.011q-.567-.002-1.135 0c-.154-.002-.305-.004-.458.009c-.122.009-.245-.021-.365.022l-.753.187a4.4 4.4 0 0 1-1.131.564c-.363-.229-.476-.49-.376-.885a1.2 1.2 0 0 1 .205-.22c.13-.111.293-.172.431-.273a.7.7 0 0 1 .15-.085c.091-.029.19-.034.285-.045a5 5 0 0 0 .506-.118a.5.5 0 0 1 .175-.013q.059.02.114.031c.133-.017.276.054.395-.057q.039-.007.076-.019c.205-.014.41-.001.615-.005c.571-.148 1.146.04 1.719-.03m2.161-7.125l-.159.121c-.096.168-.329.251-.299.492c0 .508.003 1.012-.001 1.518c-.002.424-.083.474-.532.344c-.24-.4-.108-.832-.111-1.25a.5.5 0 0 1 .15-.276s-.009-.008-.026-.006c-.077.096-.123.252-.299.16c-.053-.064-.053-.142-.042-.221c.046-.152.19-.233.264-.363a.1.1 0 0 1 .041-.041q-.025-.021-.044.026c-.091.158-.256.265-.302.451c-.081.117-.184.217-.254.344c-.075.099-.161.189-.224.296a1 1 0 0 1-.066.092c-.101.107-.222.203-.244.362a.52.52 0 0 0-.153.278c-.028.057-.078.086-.139.097a.23.23 0 0 1-.172-.057c-.104-.148-.104-.318-.084-.489c.01-.277.01-.556-.021-.83c-.003-.135.03-.263.022-.397c.012-.257-.046-.521.076-.768a.17.17 0 0 1 .133-.058c.73 0 1.457-.005 2.187.006c.109.003.334-.121.299.169");
}

.wxk_5ybpt {
  fill: var(--svg-color--a08e3e, #a08e3e);
  d: path("M31.536 29.07c.078.314-.327.281-.368.511c-.093-.061-.076-.196-.029-.201c.217-.01.26-.214.397-.31");
}

.wyue6kq7w {
  fill: var(--svg-color--961322, #961322);
  d: path("m31.86 32.389l.132-.152c.035.166.127.324.088.504c-.029.064-.081.085-.147.085c-.025-.145-.046-.294-.073-.437");
}

.x0-1cdcbi {
  fill: var(--svg-color--108131, #108131);
  d: path("M37.24 33.489c.035-.083.123-.064.185-.093c.037.063.115.136.103.188c-.021.085-.123.052-.196.052c-.003-.066-.025-.12-.092-.147");
}

.x0hsrlb3y {
  fill: var(--svg-color--4d823e, #4d823e);
  d: path("m27.25 33.08l-.192-.3c-.025-.176-.035-.339.227-.263c.09.15.088.313.05.479q-.001.042-.006.082z");
}

.x0yq5hb1v {
  fill: var(--svg-color--779132, #779132);
  d: path("M35.03 33.24c-.083-.021-.112-.085-.122-.16c-.061-.078-.145-.146-.083-.26c-.064-.092-.015-.172.022-.254c.12-.097.151.041.22.086c.085.093.029.217.068.322c.012.055.017.11.006.166c-.017.054-.044.1-.111.1");
}

.x2cfvgb5f {
  fill: var(--svg-color--87a168, #87a168);
  d: path("M36.15 35.34q.084.02.168.037a.4.4 0 0 1 .012.07q-.084.025-.17.054l-.167-.079c.025-.079.117-.031.157-.082");
}

.x4r4a_iol {
  fill: var(--svg-color--e18d0d, #e18d0d);
  d: path("M32.913 36.22v-.122c.227-.017.224.161.261.307q-.044 0-.086.002z");
}

.x7xqgll8h {
  fill: var(--svg-color--b10f21, #b10f21);
  d: path("M33.981 37.16c.213.05.279.333.525.333c-.002.136-.046.216-.199.168c-.175-.019-.315-.091-.401-.255c-.055-.105-.011-.181.075-.246");
}

.x96l0r40w {
  fill: var(--svg-color--108034, #108034);
  d: path("m26.923 31l-.406-.172c-.034-.24-.08-.479.019-.751c.133.131.295.141.462.102c.089.019.127.07.1.161c-.079.05-.134.111-.091.215c.016.139.027.275-.04.403c-.016.015-.03.026-.044.042");
}

.xewd65b6u {
  fill: var(--svg-color--43171c, #43171c);
  d: path("m27.924 36.32l.17.102l-.174.165c-.069-.091.02-.178.004-.267");
}

.xfov0_bzr {
  fill: var(--svg-color--0e3157, #0e3157);
  d: path("M35.946 27.653c-.261-.044-.43.12-.612.261c-.066.078-.19-.021-.25.078l.002.085c-.203.012-.298-.141-.414-.262c-.091-.234.105-.238.234-.299c.12-.022.093-.12.095-.201c.022-.139-.045-.225-.163-.279a.6.6 0 0 1-.102-.12c-.077-.111-.197-.112-.313-.123a.25.25 0 0 1-.184-.098a.1.1 0 0 1-.003-.103c.549-.096.973.183 1.399.459c.111.07.204.175.143.304c-.092.199.08.22.168.298");
}

.xg9rdef8p {
  fill: var(--svg-color--bf1023, #bf1023);
  d: path("M28.762 37.491c.118-.07.268-.103.325-.251c.194-.07.227.012.174.181c-.048.212-.294.103-.39.241c-.07.026-.15.066-.193-.025c-.036-.073.03-.114.084-.146");
}

.xi4nii9ec {
  fill: var(--svg-color--9d241e, #9d241e);
  d: path("M31.751 37.23q-.167 0-.333-.004a.45.45 0 0 1-.202-.17l-.077-.074c-.151-.127-.455.037-.503-.273c.04-.105.129-.089.211-.091c.281.137.606-.133.88.095c.044.17.133.34.024.517");
}

.xph-qr12w {
  fill: var(--svg-color--810b18, #810b18);
  d: path("M32.504 35.755c-.07.089-.174.082-.265.068c-.496-.079-.994-.023-1.493-.006q-.033-.028-.02-.049q.015-.021.027-.021a5.8 5.8 0 0 1 1.751.008");
}

.xqg72jbcg {
  fill: var(--svg-color--401e22, #401e22);
  d: path("m35.08 36.419l.17-.109q.028.167.059.332z");
}

.xtjzcheyy {
  fill: var(--svg-color--84242f, #84242f);
  d: path("M29.494 32.17q.041-.212.078-.423l.005-.015l.054.05c.076.165.09.327-.039.479l-.002 1.07c-.187-.374-.036-.777-.096-1.161");
}

.xvhnb-l4j {
  fill: var(--svg-color--bb1629, #bb1629);
  d: path("M30.919 33.743c.011-.058.091-.121-.011-.173c-.023-.118.081-.19.104-.294a1 1 0 0 1 .054-.104c.072-.076.139-.187.246-.041c.046.243.148.498-.146.668l-.158-.046a1 1 0 0 1-.089-.01");
}

.xzabp8bsg {
  fill: var(--svg-color--6da66d, #6da66d);
  d: path("m27.432 32.581l.013.331q-.053.037-.106.079c-.12-.149-.05-.349-.134-.508l.021-.026l.107-.055z");
}

.xzu6n4bum {
  fill: var(--svg-color--e7bf02, #e7bf02);
  d: path("M31.641 29.07c-.084.283.321.323.29.581q-.088.012-.178.021c-.136.288.064.61-.099.895a.2.2 0 0 1-.073.018c-.265-.156-.097-.407-.107-.604c-.013-.234-.056-.383-.31-.402l.004.004c-.052-.08-.041-.192.045-.186c.257.021.211-.225.323-.325q.052-.003.105-.002");
}

.y-hte9nmj {
  fill: var(--svg-color--086a0b, #086a0b);
  d: path("M36.33 34.888q-.203.062-.407.127c-.096.021-.191.037-.288.06l-.051.002c-.057-.015-.176-.048-.076-.102c.287-.161.525-.449.906-.399q0 .031.005.062c-.053.044-.149.007-.168.1c.039.044.118.066.079.15");
}

.y2bl9cb3n {
  fill: var(--svg-color--1e8433, #1e8433);
  d: path("M36.419 34.33c.072-.192.278-.164.415-.248l.08.163l-.171.09c-.11 0-.218.073-.324-.005");
}

.yd6bwobfd {
  fill: var(--svg-color--026605, #026605);
  d: path("M34.745 35.583c-.257.153-.54.165-.83.158l.503-.826c.111-.049.113-.17.169-.252c.172.094-.028.248.067.384c.186-.267.313-.546.409-.911c.122.193.155.324.104.491c-.057.18.101.091.17.116c.204-.036.223.053.091.172c-.188.17-.381.337-.595.411c.116.007.288-.06.427.072c-.118.292-.363.064-.538.132c0 0-.026-.003-.029.006c-.015.044.055.005.052.047");
}

.yfti8qnhw {
  fill: var(--svg-color--d3a105, #d3a105);
  d: path("m33.756 29.602l-.009-.193c.048-.042.112-.106.153-.021c.063.129-.028.186-.144.214");
}

.ygxs8yhql {
  fill: var(--svg-color--048942, #048942);
  d: path("m35.741 35.572l-.399.007q-.296 0-.597.004c-.077-.006-.153-.014-.288-.021c.285-.152.571.033.789-.152q.213 0 .427.003z");
}

.yiul04bqh {
  fill: var(--svg-color--de7d10, #de7d10);
  d: path("M31.29 35.944c.073.112.188.201.084.342c-.014.021-.124.01-.148-.019c-.092-.112-.047-.217.064-.323");
}

.yk6lmckem {
  fill: var(--svg-color--022e61, #022e61);
  d: path("M31.25 34.17c.133-.182.259-.299.348.029c-.127.094-.246.141-.348-.029");
}

.yk8sn5bzh {
  fill: var(--svg-color--7d1520, #7d1520);
  d: path("M30.09 33.994h.582a.48.48 0 0 1-.582 0");
}

.ykv5f1bgv {
  fill: var(--svg-color--543b3e, #543b3e);
  d: path("M33.13 35.823c-.18-.02-.375.067-.54-.068a.9.9 0 0 1 .54.068");
}

.ylb-8cbzj {
  fill: var(--svg-color--288431, #288431);
  d: path("M33.836 35.41c-.086-.132-.18-.012-.271-.007c.03-.089.046-.187.093-.262c.137-.208.292-.367.507-.078c.046.263-.068.375-.329.347");
}

.ynajhot_m {
  fill: var(--svg-color--571018, #571018);
  d: path("m36.07 35.585l.097-.087a.16.16 0 0 1 .17-.056q.004.194.011.387c-.127-.041-.198-.149-.278-.244");
}

.yobqttm_t {
  fill: var(--svg-color--526140, #526140);
  d: path("m34.32 26.995l.096-.08l.163.076c-.002.081-.006.162-.118.156c-.098-.002-.128-.07-.141-.152");
}

.yr6cfor_h {
  fill: var(--svg-color--b13543, #b13543);
  d: path("m32.08 32.74l.182.015c-.139.067-.113.188-.094.307a.35.35 0 0 1-.184.239q.023.02.015.052c-.101-.168-.07-.35-.066-.527c.042-.045.086-.08.147-.086");
}

.ys5r4cwub {
  fill: var(--svg-color--9a9a9a, #9a9a9a);
  d: path("m30.431 31.16l.17.084a.2.2 0 0 0 .003.073c.041.114.094.224.065.352q-.047.036-.102.005c-.095-.098-.082-.236-.134-.352z");
}

.ysulw4xmy {
  fill: var(--svg-color--3c3839, #3c3839);
  d: path("M31.737 32.07c.091.014.191-.01.258.081l-.003.086c-.055.038.012.185-.132.152l-.101-.057a.2.2 0 0 1-.244-.003c-.02-.165.085-.224.222-.259");
}

.yvu0ngy8a {
  fill: var(--svg-color--10253e, #10253e);
  d: path("M30.418 26.666a3.64 3.64 0 0 1 2.336-.002c-.12.104-.315.11-.372.294c-.081.033-.152.015-.222-.037c.059-.275-.06-.356-.324-.336c-.273.021-.55 0-.826-.002c-.049.045-.073.115-.141.143c-.158.052-.313.067-.451-.06");
}

.yze4cj5vg {
  fill: var(--svg-color--5e3a3f, #5e3a3f);
  d: path("M32.07 33.836c-.08-.132-.062-.282-.068-.427q.043.042.086.091l.07.254q-.043.042-.088.082");
}

.yzsk2mbgw {
  fill: var(--svg-color--51252a, #51252a);
  d: path("m29.664 35.894l.017-.073q.207-.004.413-.011c-.12.148-.28.096-.43.084");
}

.z4w70fy1k {
  fill: var(--svg-color--09325f, #09325f);
  d: path("m34.82 26.812l.016.19c.079.115.18.213.25.335c-.037.101.134.194.008.291c-.013.009-.064-.032-.097-.05c-.141-.058-.3-.07-.426-.165q-.411-.115-.824-.233c-.233-.123-.483-.032-.726-.06a.17.17 0 0 1-.116-.034c-.05-.136.007-.243.098-.339h-.002c.107-.124-.025-.303.093-.426l.49.094c.111.144-.091.347.091.473c.085.012.166-.008.246-.011c.114.016.209.104.335.075a.4.4 0 0 1 .102.021c.074.04.129.009.174-.054c.075-.09.16-.153.288-.107");
}

.z7hff9b-g {
  fill: var(--svg-color--25700b, #25700b);
  d: path("M35.09 31.586q.035-.012.073-.009q-.001.051-.005.102c-.062-.002-.074-.041-.068-.093");
}

.za_dgvb9q {
  fill: var(--svg-color--ca1226, #ca1226);
  d: path("M34.936 37.41c.234-.2.511-.383.374-.766c-.038-.105-.146-.184-.126-.313c.026-.176.133-.31.24-.441q.063-.092.13-.184a.8.8 0 0 1 .285-.184a.4.4 0 0 1 .228.002c.124.058.215.157.318.24a.3.3 0 0 1 .089.145a.24.24 0 0 1-.067.207c-.09.081-.189.153-.266.248c-.064.08-.107.172-.15.264c-.031.084-.1.138-.149.208c-.187.331-.366.667-.741.825c-.15.046-.317.116-.26-.165a.18.18 0 0 1 .095-.086");
}

.zb2ikq3tj {
  fill: var(--svg-color--328b3b, #328b3b);
  d: path("M34.915 30.23c.028 0 .06-.001.088-.003c.273.045.257.274.303.465a.37.37 0 0 1-.12.309c-.063.022-.107-.002-.147-.048c-.082-.118-.115-.263-.202-.381c-.041-.097-.194-.138-.164-.261c.028-.127.16-.046.242-.081");
}

.zbs650pwr {
  fill: var(--svg-color--7f8f2b, #7f8f2b);
  d: path("m36.34 29.736l-.1.048c-.082.015-.165.041-.231-.037c.11-.066.014-.547.343-.17a.09.09 0 0 1-.008.086a.1.1 0 0 0-.004.073");
}

.zgbg7wxys {
  fill: var(--svg-color--b61022, #b61022);
  d: path("m32.496 37.23l.01-.391q.032-.051.085-.025c.066.163.335-.05.358.192c-.141.027-.005.382-.288.239c-.053-.003-.109-.012-.165-.015");
}

.zj6zbtbcv {
  fill: var(--svg-color--278431, #278431);
  d: path("M34.738 29.338q.087.033.17.067l.091.172c-.153.064-.309.137-.483.089c.071-.109.322-.102.222-.328");
}

.zkt--k02j {
  fill: var(--svg-color--c78611, #c78611);
  d: path("M32.757 30.25q.015.085.033.168l-.088.17a.2.2 0 0 1-.111.103a.1.1 0 0 1-.093-.028c-.072-.238.098-.324.259-.413");
}

.zlw4xvb0u {
  fill: var(--svg-color--04690a, #04690a);
  d: path("m27.09 30.996l-.093.479c-.207-.021-.098-.141-.072-.234v-.237l.002-.019a.14.14 0 0 1 .085-.036a.14.14 0 0 1 .078.047");
}

.zmpdg21qa {
  fill: var(--svg-color--e3e3e3, #e3e3e3);
  d: path("m32.33 31.33l-.502.49c-.064-.032-.072-.093-.074-.154c.123-.229.272-.417.576-.336");
}

.znahiqbbm {
  fill: var(--svg-color--242c37, #242c37);
  d: path("m30.905 26.653l.104-.07c-.094.16.1.373-.091.516l-.003-.183a.3.3 0 0 1-.059-.099a.26.26 0 0 1 .049-.164");
}

.zo7j-nbdd {
  fill: var(--svg-color--6fa056, #6fa056);
  d: path("m35.31 33.33l-.063-.172q.048-.071.091.002q.142.152.013.314z");
}

.zp_krbe0q {
  fill: var(--svg-color--016707, #016707);
  d: path("M35.839 32.409c-.087-.25-.244-.479-.262-.751c.152-.084.075-.254.134-.374l.039-.039h.085h-.003c.053.068.168.029.208.117c-.106.228.2.056.188.194c.062.301-.095.532-.232.771z");
}

.zt_d_0ysi {
  fill: var(--svg-color--e1dbc7, #e1dbc7);
  d: path("M30.431 31.16c.02-.15-.093-.33.103-.441q.082.09.164.184c.076.045.14.098.148.192l-.245.149c-.104.066-.13-.02-.17-.084");
}

.ztrngybee {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M37 27V10H26v17H0v10h26v17h11V37h27V27z");
}

.zwcg4qb0x {
  fill: var(--svg-color--888329, #888329);
  d: path("m29.08 26.864l-.087-.209c.141-.123.25-.094.279.086c.023.136-.057.191-.192.123");
}

.zweyqt6oe {
  fill: var(--svg-color--bb8512, #bb8512);
  d: path("M33.06 29.911c-.087.127-.149.279-.311.338c-.008-.169.117-.252.222-.347q.051-.05.089.009");
}

.zwxfjebkz {
  fill: var(--svg-color--0a7c2b, #0a7c2b);
  d: path("M28.09 33.898c.063.053.217-.065.208.097c-.008.164-.274.398.173.392c.126-.002-.075.35-.373.447c-.084.091.029.222-.063.311c-.07.067-.14.031-.205-.003c-.076-.052-.146-.109-.22-.163a.5.5 0 0 1-.078-.079a1 1 0 0 1-.101-.202a.6.6 0 0 1-.023-.116c-.011-.158-.021-.318.03-.476a.34.34 0 0 1 .105-.137c.174-.091.364-.044.547-.071");
}

.zyett0myk {
  fill: var(--svg-color--dfe4cc, #dfe4cc);
  d: path("M36.667 30.844q-.044.015-.087.026l.012-.193c.079-.08.17-.121.286-.101c-.09.075-.183.148-.211.268");
}

.zys377bau {
  fill: var(--svg-color--96ac65, #96ac65);
  d: path("M34.592 34.08c-.015-.105.045-.17.115-.248c.079.136.052.243-.021.345c-.057-.008-.064-.064-.094-.097");
}

</style>
