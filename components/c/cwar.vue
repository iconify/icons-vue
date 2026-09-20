<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGxAZ4ieSu)" class="aj2tjwbjj"/><path fill="url(#SVGjpDgIymm)" class="ickh3ccbv"/><path fill="url(#SVGn80Wec7Y)" class="h0k17ab9z"/><path fill="url(#SVGI8Y65cyx)" class="b_09zpa5m"/><path fill="url(#SVGBvkH4dJq)" class="fiu2kzb-y"/><path fill="url(#SVGr2S5OtXF)" class="c6cfh1kvf"/><path fill="url(#SVGadm1Naop)" class="kj2yam4_x"/><path fill="url(#SVGAKOLjdJO)" class="c34vzvbng"/><path fill="url(#SVGCS1AsdBb)" class="wc6urhb5i"/><path fill="url(#SVG9CCTgd2r)" class="lzu1c-brp"/><path fill="url(#SVGgtkzrdjx)" clip-rule="evenodd" class="h9-cwg56x"/><path class="tkjga3bna"/><path fill="url(#SVGMRFh8b4D)" class="s-8k_ob6f"/><path fill="url(#SVGxcr8kMPg)" class="y9u3454wt"/><path fill="url(#SVGOFDMzewp)" class="hx_iedbzl"/><path fill="url(#SVGMzyANdVB)" class="pr4jbgbab"/><path fill="url(#SVG0asThCpN)" class="x6vbh2btn"/><path fill="url(#SVGp5wlvctt)" class="v1gs2pz0a"/><path fill="url(#SVGbJMxtduw)" clip-rule="evenodd" class="nvv7xfbka"/><path fill="url(#SVGRI9JQeKi)" class="rwlxc_-hy"/><path fill="url(#SVGp8ZHXcwg)" class="w8zze0b1m"/><path class="a38sztbaa"/><path class="hsjsmibqt"/><defs><linearGradient id="SVGxAZ4ieSu" x1="13.474" x2="12.828" y1="3.805" y2="21.034" gradientUnits="userSpaceOnUse"><stop class="bd72xxbkx"/><stop offset=".18" class="ub-6xfjiy"/><stop offset=".39" class="ifuze0i5a"/><stop offset=".52" class="dhr4twb3r"/><stop offset=".77" class="tb_q_pbom"/><stop offset="1" class="e2g0nlbrt"/></linearGradient><linearGradient id="SVGjpDgIymm" x1="4.785" x2="11.588" y1="8.802" y2="18.936" gradientUnits="userSpaceOnUse"><stop class="xhz0a0yat"/><stop offset=".61" class="w90bhlbxp"/><stop offset="1" class="b9pdaabsh"/></linearGradient><linearGradient id="SVGn80Wec7Y" x1="4.154" x2="20.464" y1="3.034" y2="19.772" gradientUnits="userSpaceOnUse"><stop class="ogmq57gyo"/><stop offset="1" class="jmrlviers"/></linearGradient><linearGradient id="SVGI8Y65cyx" x1="4.125" x2="19.569" y1="3.048" y2="19.225" gradientUnits="userSpaceOnUse"><stop class="u4afi8bui"/><stop offset="1" class="nj75-ibfm"/></linearGradient><linearGradient id="SVGBvkH4dJq" x1="4.124" x2="8.865" y1="3.001" y2="22.601" gradientUnits="userSpaceOnUse"><stop offset=".47" class="anzkasxyn"/><stop offset="1" class="asv2k-b4i"/></linearGradient><linearGradient id="SVGr2S5OtXF" x1="6.052" x2="12.51" y1="4.095" y2="23.192" gradientUnits="userSpaceOnUse"><stop class="nz7ytzbbn"/><stop offset=".49" class="fu1z21blc"/><stop offset=".76" class="vp11k1byg"/><stop offset="1" class="ab16m00kq"/></linearGradient><linearGradient id="SVGadm1Naop" x1="7.121" x2="11.562" y1="3.015" y2="21.769" gradientUnits="userSpaceOnUse"><stop class="ap0--cbue"/><stop offset=".41" class="mjcl0fb5o"/><stop offset=".56" class="su4r9jbcc"/><stop offset="1" class="apf9xrb8k"/></linearGradient><linearGradient id="SVGAKOLjdJO" x1="5.639" x2="9.114" y1="2.542" y2="21.677" gradientUnits="userSpaceOnUse"><stop class="znk-7xb2j"/><stop offset=".35" class="r3alx330p"/><stop offset=".65" class="fy3x7tbar"/><stop offset="1" class="cl6ex92nj"/></linearGradient><linearGradient id="SVGCS1AsdBb" x1="12.019" x2="12.019" y1="3" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="cmkju7bum"/><stop offset="1" class="v6pb5cb6p"/></linearGradient><linearGradient id="SVG9CCTgd2r" x1="11.999" x2="11.999" y1="3.001" y2="20.961" gradientUnits="userSpaceOnUse"><stop class="m7zpx_zla"/><stop offset="1" class="jm6wz4bih"/></linearGradient><linearGradient id="SVGgtkzrdjx" x1="11.999" x2="11.999" y1="3.006" y2="21" gradientUnits="userSpaceOnUse"><stop class="dzt0l2c3w"/><stop offset=".54" class="eg5f20k3o"/><stop offset="1" class="a6zmztb9a"/></linearGradient><linearGradient id="SVGMRFh8b4D" x1="20.604" x2="1.234" y1="3.065" y2="19.515" gradientUnits="userSpaceOnUse"><stop offset=".25" class="adf0nu6hs"/><stop offset=".38" class="csou9tqec"/><stop offset=".51" class="h10di2y6j"/><stop offset="1" class="f5y_yf0ix"/></linearGradient><linearGradient id="SVGxcr8kMPg" x1="19.047" x2="1.178" y1="3.066" y2="19.251" gradientUnits="userSpaceOnUse"><stop class="l52dqccet"/><stop offset=".36" class="xm9oltbko"/><stop offset="1" class="hrnp1g9bf"/></linearGradient><linearGradient id="SVGOFDMzewp" x1="19.662" x2="8.752" y1="1.666" y2="23.363" gradientUnits="userSpaceOnUse"><stop class="g-5z62bsv"/><stop offset="1" class="js94kkmqa"/></linearGradient><linearGradient id="SVGMzyANdVB" x1="19.541" x2="-.931" y1="-.152" y2="36.19" gradientUnits="userSpaceOnUse"><stop class="u01m3lmub"/><stop offset="1" class="m5_20ybwm"/></linearGradient><linearGradient id="SVG0asThCpN" x1="11.867" x2="11.867" y1="3" y2="21.028" gradientUnits="userSpaceOnUse"><stop class="lsctsibdo"/><stop offset=".54" class="jn24rbbbu"/><stop offset="1" class="j2ooxcbrl"/></linearGradient><linearGradient id="SVGp5wlvctt" x1="17.564" x2="15.674" y1="4.262" y2="21.423" gradientUnits="userSpaceOnUse"><stop class="j1ae9bchu"/><stop offset=".44" class="uabxjjb7w"/></linearGradient><linearGradient id="SVGbJMxtduw" x1="11.997" x2="11.997" y1="2.995" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="s3x0-rb2d"/><stop offset=".3" class="f_1wm2bfr"/><stop offset=".65" class="yyhdiub6i"/><stop offset="1" class="o8b3n_mlc"/></linearGradient><linearGradient id="SVGRI9JQeKi" x1="18.48" x2="12.838" y1="2.999" y2="22.232" gradientUnits="userSpaceOnUse"><stop class="trzkvt_lc"/><stop offset=".34" class="c3sygxl8w"/><stop offset=".46" class="nxhea2bra"/><stop offset="1" class="b0q8ftb0o"/></linearGradient><linearGradient id="SVGp8ZHXcwg" x1="18.48" x2="12.838" y1="2.999" y2="22.232" gradientUnits="userSpaceOnUse"><stop class="bz2v5bcyk"/><stop offset=".46" class="gz1v3ccid"/><stop offset="1" class="x1h0_9f7j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cwar" /></template>
<style>
.a38sztbaa {
  fill: var(--svg-color--4afffe, #4afffe);
  d: path("M14 13.267c.381.462 1.359.247 2.183-.48c.825-.728 1.184-1.693.803-2.155c-.382-.463-1.36-.248-2.184.48s-1.184 1.692-.802 2.155");
}

.a6zmztb9a {
  stop-color: var(--svg-color--f8c5c4, #f8c5c4);
}

.ab16m00kq {
  stop-color: var(--svg-color--5a3a3d, #5a3a3d);
}

.adf0nu6hs {
  stop-color: var(--svg-color--4a6266, #4a6266);
}

.aj2tjwbjj {
  d: path("M17.922 20.971c-.816-.022-2.328-.366-1.811-1.53c.652-1.451 1.687-1.873 2.801-1.704c1.114.163.968-1.001.641-1.001l-.236-.023c-.573-.068-1.901-.22-3.206.619c-1.541.984-2.115.995-2.492-.304c-.382-1.305 1.738-1.102 2.492-.787c.76.32 1.811-1.671 2.047-2.644c.045-.208.163-.5.293-.844c.495-1.277 1.265-3.262.056-4.162a3.2 3.2 0 0 0-1.181-.338c-.473-.073-.799-.118-.636-.472a5.1 5.1 0 0 1 1.98-1.378c1.069-.332 1.294-1.317 1.176-1.71c-.124-.394-2.07-2.329-4.882-1.48a5.4 5.4 0 0 0-2.003.979c.017.163.006.371-.028.641c-.225 1.654-.833 1.834-1.434 1.924c-.389.056-.608.236-.805.394c-.112.084-.208.163-.32.208a1.13 1.13 0 0 1-.563.101c.574.619 1.783 2.256 2.07 3.938c.371 2.21-.276 4.86-.866 7.278a56 56 0 0 0-.529 2.306z");
}

.anzkasxyn {
  stop-color: var(--svg-color--fffdfa, #fffdfa);
}

.ap0--cbue {
  stop-color: var(--svg-color--5a4f4e, #5a4f4e);
}

.apf9xrb8k {
  stop-color: var(--svg-color--5c4347, #5c4347);
}

.asv2k-b4i {
  stop-color: var(--svg-color--e1d6d8, #e1d6d8);
}

.b_09zpa5m {
  d: path("m9.79 21l.259-.71l-4.005-3.504L9.8 20.341L9.666 21z");
}

.b0q8ftb0o {
  stop-color: var(--svg-color--000600, #000600);
}

.b9pdaabsh {
  stop-color: var(--svg-color--9e3543, #9e3543);
  stop-opacity: 0.41;
}

.bd72xxbkx {
  stop-color: var(--svg-color--11638b, #11638b);
  stop-opacity: 0.2;
}

.bz2v5bcyk {
  stop-color: var(--svg-color--989fa0, #989fa0);
}

.c34vzvbng {
  d: path("M5.373 5.957c1.93.124 3.195.86 4.016 1.834a6.53 6.53 0 0 1 1.423 5.81l-.011.045l.467.27l-1.665 3.96l-.09.253h.011l1.93-4.23l-.479-.236c.377-1.536.197-3.881-1.35-5.782a5.12 5.12 0 0 0-4.252-1.924");
}

.c3sygxl8w {
  stop-color: var(--svg-color--8bc9d3, #8bc9d3);
}

.c6cfh1kvf {
  d: path("m5.852 12.343l2.666 2.137l-.607 2.115l.264-1.946z");
}

.cl6ex92nj {
  stop-color: var(--svg-color--f9edf1, #f9edf1);
}

.cmkju7bum {
  stop-color: var(--svg-color--bfb1b1, #bfb1b1);
}

.csou9tqec {
  stop-color: var(--svg-color--939d9f, #939d9f);
}

.dhr4twb3r {
  stop-color: var(--svg-color--0b9bb4, #0b9bb4);
}

.dzt0l2c3w {
  stop-color: var(--svg-color--ffabb8, #ffabb8);
}

.e2g0nlbrt {
  stop-color: var(--svg-color--0e3650, #0e3650);
  stop-opacity: 0.45;
}

.eg5f20k3o {
  stop-color: var(--svg-color--ff949e, #ff949e);
}

.f_1wm2bfr {
  stop-color: var(--svg-color--abfeff, #abfeff);
}

.f5y_yf0ix {
  stop-color: var(--svg-color--131f1f, #131f1f);
}

.fiu2kzb-y {
  d: path("M8.664 14.486L5.778 12.27l2.396 2.38l-.416 3.07l.9-3.234z");
}

.ft5dv1b6b {
  fill: none;
}

.fu1z21blc {
  stop-color: var(--svg-color--753939, #753939);
}

.fy3x7tbar {
  stop-color: var(--svg-color--f4eae9, #f4eae9);
}

.g-5z62bsv {
  stop-color: var(--svg-color--6b6f72, #6b6f72);
}

.gz1v3ccid {
  stop-color: var(--svg-color--d5fdfd, #d5fdfd);
}

.h0k17ab9z {
  d: path("M10.2 20.269L4.125 14.84v.13l5.681 5.371l-.14.658h.27l.27-.731z");
}

.h10di2y6j {
  stop-color: var(--svg-color--324242, #324242);
}

.h9-cwg56x {
  fill-rule: evenodd;
  d: path("M8.737 4.947c.056.112.146.382 0 .545c-.186.203.303.45.315.225v-.163c0-.264 0-.641.225-.506c.225.034.32.073.377.096c.028.01.044.022.067.022c.034 0 .073-.022.186-.084l.056-.034l.096-.056c.416-.26 1.248-.765 1.98-.158c.067.085.174.293.1.416c-.1.152-.196.394-.1.557c.1.163.01.416-.614.49c-.337.045-.579.225-.77.376c-.17.124-.304.225-.428.18l-.152-.056c-.157-.062-.241-.101-.421.056c-.113.102-.276.006-.462-.1c-.191-.113-.416-.248-.641-.186c-.337.084-.343.46-.343.708c0 .073 0 .135-.011.175c-.017.09-.113.13-.192.152c-.084.033-.146.056-.028.129l.135.073c.124.056.147.073-.05.214c-.253.191-.512.523-.208.85c0 .061-.057.095-.124.129c-.113.056-.236.112-.158.337c0 .056-.01.101-.017.146c-.028.118-.045.208.13.208c.067.023.225.096.292.214c.04.073 0 .101-.04.13c-.044.028-.078.056.04.123c.096.062.214.04.327.012c.146-.029.28-.057.348.106c.113.287.147.788 0 .872c-.118.068.118.265.253.355a.4.4 0 0 1 .102-.355c.067-.067.112-.067.168-.067s.141.005.282-.073c.14-.074.163-.141.168-.186c.017-.05.023-.073.141-.067c.225.01.084-.479-.135-.479c-.14 0-.14-.01-.169-.067a1.4 1.4 0 0 0-.123-.175c-.197-.213-.338-.202-.467-.1c-.293.224-.602.19-.675.1a2 2 0 0 1-.09-.123a.7.7 0 0 0-.203-.22c-.073-.078-.073-.14-.067-.19c0-.035 0-.063-.017-.085c-.062-.079.005-.191.377-.152c.084.04.236.067.185-.113c-.062-.23.282-.112.304 0c.028.113.186.377.281.186a.3.3 0 0 0 .017-.253a.3.3 0 0 1-.017-.163a.4.4 0 0 0 0-.163a.45.45 0 0 1 .04-.293c.095-.225.084-.242-.085-.281c-.168-.034-.433-.124-.31-.326c.074-.118.113-.135.142-.14c.016-.007.028-.012.045-.052c.01-.033-.006-.14-.029-.27c-.033-.19-.078-.416-.01-.46c.112-.08.247-.051.517.1c.185.107.303.062.41.029a.5.5 0 0 1 .14-.029c.057 0 .09-.016.125-.039c.056-.028.118-.062.28-.022c.17.039.215.005.282-.04a.5.5 0 0 1 .118-.079a.4.4 0 0 0 .13-.09c.073-.056.135-.118.348-.112c.169.011.225-.068.276-.14c.045-.068.084-.13.202-.124h.006c.248.016.641.033.731-.366c.05-.259.09-.332.135-.416l.096-.203c.096-.264.225-1.153 0-1.237c-.067-.028-.118-.068-.169-.101c-.118-.085-.225-.17-.529-.029l-.247.113c-.146.079-.152.084-.506.101h-.366c-.315-.011-.602-.022-.917.191c-.258.18-.506.197-.692.214c-.112.011-.208.023-.258.062c-.113.096-.135.191-.135.225zm.618 5.58a.25.25 0 0 0-.213-.13c-.163 0-.237-.05-.248-.174s.023-.107.186-.012l.022.012c.102.056.158.022.197 0c.04-.017.068-.034.113 0c.095.073.056.303-.057.303m-.41.264c.056 0 .124.05.146.073c.056 0 .056-.281-.056-.287c-.13-.017-.169.214-.09.214m-.27-1.783c.056-.006.169-.028.197-.09c.033-.073.073.225-.012.242c-.09.01-.163-.102-.185-.152");
}

.hrnp1g9bf {
  stop-color: var(--svg-color--bec3c7, #bec3c7);
}

.hsjsmibqt {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.278 13.676l.208-1.457l2.548-1.48l.13.394z");
}

.hx_iedbzl {
  d: path("m19.306 18.356l-1.519 2.53l1.249-2.795l.838-.315v.315z");
}

.ickh3ccbv {
  d: path("M8.884 6.385c-2.16.264-2.38-.928-2.217-1.553c.26-.635 2.217-.495 2.745-.725c.523-.225 1.721-.152 2.307-.265c.59-.112 1.434-.669 1.214.99c-.224 1.654-.832 1.834-1.434 1.924c-.596.084-.804.467-1.125.602a1.13 1.13 0 0 1-.562.101c.573.619 1.783 2.256 2.07 3.938c.495 2.947-.816 6.66-1.395 9.59H4.26v-.872c.405-1.94 4.1-2.419 4.365-3.29c.27-.872-1.406-1.041-3.19-2.408c-1.788-1.361-1.36-6.474 0-6.958c1.356-.478 1.542.748 1.97.585c.427-.169.438-1.367.77-1.49c.332-.13 1.175 0 1.637-.09c.466-.09.528.022.883-.08c.354-.1.332-.286 1.03-.488c.697-.203-.113-.827-.591-1.07c-.383-.19-.934.45-1.16.788c-.517 0-.247.77-1.09.77");
}

.ifuze0i5a {
  stop-color: var(--svg-color--176c96, #176c96);
  stop-opacity: 0.56;
}

.j1ae9bchu {
  stop-color: var(--svg-color--96afb4, #96afb4);
}

.j2ooxcbrl {
  stop-color: var(--svg-color--a4b9be, #a4b9be);
}

.jm6wz4bih {
  stop-color: var(--svg-color--f5dfe1, #f5dfe1);
}

.jmrlviers {
  stop-color: var(--svg-color--e3eeea, #e3eeea);
}

.jn24rbbbu {
  stop-color: var(--svg-color--d4e1e9, #d4e1e9);
}

.js94kkmqa {
  stop-color: var(--svg-color--efefef, #efefef);
}

.kj2yam4_x {
  d: path("M9.632 7.882C8.602 6.605 6.949 5.688 4.446 6.03c4.134-.202 6.665 3.859 5.917 7.312l-4.061-2.036l4.725 2.734l-1.558 4.201l1.985-4.342l-.478-.236a6.86 6.86 0 0 0-1.35-5.782z");
}

.l52dqccet {
  stop-color: var(--svg-color--a5b8be, #a5b8be);
}

.lsctsibdo {
  stop-color: var(--svg-color--6c898d, #6c898d);
}

.lzu1c-brp {
  d: path("M4.18 12.225c.456-.169.788-.68.788-1.294c0-.618-.332-1.13-.788-1.293v.135c.383.185.653.646.653 1.18c0 .54-.27.996-.647 1.182v.084z");
}

.m5_20ybwm {
  stop-color: var(--svg-color--555557, #555557);
}

.m7zpx_zla {
  stop-color: var(--svg-color--d6c2c4, #d6c2c4);
}

.mjcl0fb5o {
  stop-color: var(--svg-color--b3908f, #b3908f);
}

.nj75-ibfm {
  stop-color: var(--svg-color--5e5d5b, #5e5d5b);
}

.nvv7xfbka {
  fill-rule: evenodd;
  d: path("M13.816 7.499c-.13.04-.118.169-.101.225v.011l.011.023s.017 0 .056-.023l.017-.005c.09-.04.135-.04.197.1c.04.08-.017.102-.096.13a.5.5 0 0 0-.185.113c-.085.079-.05.112-.006.152c.028.028.056.056.056.112l-.005.05c-.017.096-.023.17.101.304c.112.119.095.158.045.254l-.045.084c-.023.056-.045.073-.062.084c-.028.023-.04.028 0 .282c.045.28.113.292.186.309c.04.011.073.017.112.05c.118.102.045.136-.04.085c-.084-.05-.168.056-.123.152c.028.056.085.073.135.09c.045.011.084.028.073.062c-.011.04-.056.028-.095.022c-.045-.011-.09-.022-.113.017c-.034.079.073.214.208.152a2 2 0 0 0 .225-.158c.214-.151.49-.36.608-.337c.107.022.13.067.168.135a1 1 0 0 0 .113.169c.157.18.197.27.124.354c-.057.073-.068.281-.062.383q.437-.15.821-.405c.04-.062.023-.118.006-.175a.27.27 0 0 1-.006-.157c.011-.05.079-.057.14-.068c.096-.017.192-.034.13-.185c-.084-.186-.135-.192-.247-.209c-.04-.005-.09-.01-.147-.028c-.123-.039-.174-.078-.23-.112a.5.5 0 0 0-.164-.09c-.072-.028-.112-.13-.151-.242c-.057-.146-.113-.31-.276-.383c-.191-.084-.225-.253-.259-.393a.5.5 0 0 0-.056-.163c-.04-.057-.034-.13-.028-.203c0-.079.011-.152-.045-.202a.45.45 0 0 0-.186-.057c-.09-.016-.197-.033-.28-.118c-.09-.09 0-.174.078-.242c.045-.045.09-.084.067-.112c-.028-.05-.056-.023-.095.022l-.085.09c-.112.09-.135-.163-.135-.303c0-.085.017-.08.056-.062c.017.005.045.017.08.011c.084-.011.073-.062 0-.124c-.034-.028-.057-.011-.085.006c-.04.028-.09.056-.186-.034c-.163-.152.073-.304.085-.174c.011.124.073.202.146.101c.028-.045 0-.096-.017-.146c-.034-.068-.056-.124.09-.113c.259.028.506.045.72-.022c.113-.028.186-.107.248-.169c.067-.067.123-.13.197-.118a.8.8 0 0 0 .314-.079c.08-.05.08-.079.08-.112c0-.045 0-.09.14-.18c.343-.22.422-.405.478-.535l.028-.056c.045-.096.09-.101.169-.107c.028 0 .056 0 .095-.011c.057-.006.09 0 .119.006c.039.01.067.016.14-.057c.124-.112.197-.213.186-.365c-.017-.152-.073-.315-.383-.647c-.225-.242-.382-.203-.528-.163c-.057.011-.107.028-.158.028a1 1 0 0 1-.202-.034a.55.55 0 0 0-.383-.006c-.118.045-.197.057-.27.074s-.135.028-.23.067a1 1 0 0 1-.27.04c-.175.016-.366.028-.467.146c-.107.13-.192.135-.321.146c-.062.006-.135.011-.225.034c-.281.062-.382.123-.208.427c.118.22.107.242.056.32c-.011.035-.04.08-.056.153c-.073.236.112.405.208.326a.2.2 0 0 0 .062-.084c.011-.029.017-.04.067-.04c.057 0 .102-.056.147-.124a.34.34 0 0 1 .1-.118c.057-.045-.01-.09-.09-.14c-.055-.04-.123-.085-.157-.14c-.073-.125-.022-.265.073-.265c.057 0 .057.056.057.112c-.006.04-.006.079.022.079c.056 0 .146-.113.158-.383c.005-.18.225-.219.388-.247a.5.5 0 0 0 .169-.056c.056-.034.236-.057.427-.085c.208-.028.422-.056.484-.1c.056-.04.084-.035.14-.018c.074.017.186.05.45.017c.462-.067.681.557.72.68c.023.09-.056.113-.146.147l-.112.045c-.073.04-.079.017-.079-.006c0-.017-.006-.033-.034-.033c-.034 0-.04.022-.056.061a.4.4 0 0 1-.056.13c-.04.073-.073.09-.113.112s-.079.04-.13.09a.7.7 0 0 0-.095.113a.27.27 0 0 1-.146.13c-.073.027-.084.061-.09.106a.14.14 0 0 1-.056.096a1 1 0 0 0-.208.19l-.113.113c-.045.04-.09.006-.14-.022c-.046-.034-.102-.068-.17-.056c-.061.01-.072.045-.084.078c-.01.04-.028.085-.112.124a.23.23 0 0 0-.113.113c-.022.039-.033.073-.1.09c-.08.022-.09-.012-.102-.057a.2.2 0 0 0-.056-.112c-.08-.056-.09-.045-.152-.006l-.085.05l-.073.04c-.073.045-.095.057-.22 0c-.112-.056-.28.085-.393.186l-.118.09c-.067.034-.163 0-.259-.045l-.123-.045c-.136-.04-.136.152.05.18c.146.017.23.112.259.163c-.034.011-.062 0-.096-.006c-.045-.016-.09-.028-.13.045c-.033.08.012.08.063.085c.05 0 .107 0 .112.067c.006.079.079.113.152.152q.061.026.107.073l.017.023c.056.073.123.146-.017.191m.877 1.294c.214-.073.31.152.332.281l.023.377c-.203.09-.658.264-.844.225c-.23-.05-.259-.416-.034-.495l.152-.045c.13-.04.203-.056.169-.113c-.056-.078-.068-.146.203-.23m.957 1.552c-.074.017-.22.017-.208-.112c.01-.17.134-.17.208-.101c.073.061.095.18 0 .213m-.282-.63c.107.04.158.017.17 0c.236-.112.342-.09.393.04a.3.3 0 0 0 .067.106c.023.023.04.045.057.107c.022.113-.113.05-.237-.039c-.095-.073-.168-.056-.292-.04l-.113.017c-.208.023-.18-.241-.045-.19M13.945 5.26c-.067.023-.191.073-.129.102a.15.15 0 0 0 .073.022c.04.011.062.017.073.056c.011.057.169-.04.169-.078c0-.029-.124-.08-.186-.102m.124.962c0 .04-.034.079-.073.079a.073.073 0 0 1-.073-.079c0-.04.034-.073.073-.073c.04 0 .073.034.073.073m2.194 3.049c-.113-.028-.338-.298-.433-.428c-.023-.067-.045-.174.062-.067c.135.14.247.191.466.112c.226-.073.377-.045.563.13c.186.18-.186.433-.354.416a.26.26 0 0 1-.18-.084c-.034-.029-.068-.062-.124-.08m-.063-.19c-.056-.09.112-.068.157-.062h.012a.4.4 0 0 0 .157.168c.056.04.096.068.062.096c-.04.045-.073.023-.118-.011a.5.5 0 0 0-.101-.05c-.113-.04-.113-.04-.17-.141");
}

.nxhea2bra {
  stop-color: var(--svg-color--7be8fc, #7be8fc);
}

.nz7ytzbbn {
  stop-color: var(--svg-color--9e4849, #9e4849);
}

.o8b3n_mlc {
  stop-color: var(--svg-color--f7fffd, #f7fffd);
}

.ogmq57gyo {
  stop-color: var(--svg-color--e8e2e2, #e8e2e2);
}

.pr4jbgbab {
  d: path("m19.874 17.855l-.714.27l-.613 1.497l.759-1.266l.568-.265z");
}

.r3alx330p {
  stop-color: var(--svg-color--f3e8e4, #f3e8e4);
}

.rwlxc_-hy {
  d: path("m14.53 18.597l-.45.304c-1.732-3.23-1.546-6.846.732-9.641c1.249-1.525 3.026-2.616 5.034-2.706v.214a8.2 8.2 0 0 0-4.455 2.655c-2.11 2.62-2.542 5.298-.855 9.168z");
}

.s-8k_ob6f {
  d: path("m17.67 16.5l-2.987 2.097l-.113-.112l2.695-2.267l.54-1.367l1.26-.9l-1.08 1.215l-.315 1.328z");
}

.s3x0-rb2d {
  stop-color: var(--svg-color--dffdff, #dffdff);
}

.su4r9jbcc {
  stop-color: var(--svg-color--d2a3a3, #d2a3a3);
}

.tb_q_pbom {
  stop-color: var(--svg-color--072230, #072230);
  stop-opacity: 0.65;
}

.tkjga3bna {
  fill: var(--svg-color--fdfefc, #fdfefc);
  d: path("M6.914 10.981v-1.12l3.156 2.33l-.332.264l-2.824-1.48z");
}

.trzkvt_lc {
  stop-color: var(--svg-color--a6a9a9, #a6a9a9);
}

.u01m3lmub {
  stop-color: var(--svg-color--514f50, #514f50);
}

.u4afi8bui {
  stop-color: var(--svg-color--686264, #686264);
}

.uabxjjb7w {
  stop-color: var(--svg-color--93b6b8, #93b6b8);
}

.ub-6xfjiy {
  stop-color: var(--svg-color--02849d, #02849d);
  stop-opacity: 0.34;
}

.v1gs2pz0a {
  d: path("M19.875 10.913c-.562.08-1.035.552-1.035 1.125c0 .467.281.86.68 1.041a1.13 1.13 0 0 1-.455-.934c0-.54.366-.99.81-1.074z");
}

.v6pb5cb6p {
  stop-color: var(--svg-color--ebd8d2, #ebd8d2);
}

.vp11k1byg {
  stop-color: var(--svg-color--886e71, #886e71);
}

.w8zze0b1m {
  d: path("m14.244 18.794l-.163.107c-1.733-3.23-1.547-6.846.73-9.641c1.25-1.525 3.027-2.616 5.035-2.706v.04c-1.04.09-3.589.545-5.422 3.374a8.4 8.4 0 0 0-.18 8.826");
}

.w90bhlbxp {
  stop-color: var(--svg-color--b81214, #b81214);
}

.wc6urhb5i {
  d: path("M4.18 8.551c.973.045 1.744.979 1.744 2.126c0 .743-.32 1.395-.816 1.778a2.25 2.25 0 0 0 1.035-1.94c0-1.21-.86-2.194-1.923-2.194h-.034v.23z");
}

.x1h0_9f7j {
  stop-color: var(--svg-color--d2d7dd, #d2d7dd);
}

.x6vbh2btn {
  d: path("m19.875 10.334l-.186-.01c-.805 0-1.485.781-1.485 1.743c0 .967.652 1.744 1.462 1.744l.158-.006c-.703-.096-1.249-.804-1.249-1.66c0-.871.585-1.585 1.3-1.664z");
}

.xhz0a0yat {
  stop-color: var(--svg-color--6c0808, #6c0808);
  stop-opacity: 0.57;
}

.xm9oltbko {
  stop-color: var(--svg-color--d2d8de, #d2d8de);
}

.y9u3454wt {
  d: path("m14.627 18.535l2.756-2.216l.517-1.395l.923-.697l.242-.276l-1.26.9l-.54 1.367l-2.695 2.26z");
}

.yyhdiub6i {
  stop-color: var(--svg-color--b1f7fc, #b1f7fc);
}

.znk-7xb2j {
  stop-color: var(--svg-color--8a7f79, #8a7f79);
}

</style>
