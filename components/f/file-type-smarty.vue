<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGBROSjemU" x1="13.9" x2="18.1" y1="29.2" y2="29.2" gradientUnits="userSpaceOnUse"><stop offset=".034" class="i8kc83bgm"/><stop offset=".178" class="o-opznbct"/><stop offset=".219" class="wc64txvkk"/><stop offset=".309" class="jkrnbsmxf"/><stop offset=".481" class="uaxk0gb2x"/><stop offset=".716" class="sqeir4bkd"/><stop offset=".719"/><stop offset="1" class="db7qn2upl"/></linearGradient><linearGradient id="SVGBaHPyczq" x1="15.2" x2="16.8" y1="29.7" y2="29.7" href="#SVGBROSjemU"/><linearGradient id="SVGPIrlMdBU" x1="15.3" x2="16.7" y1="29.9" y2="29.9" gradientUnits="userSpaceOnUse"><stop offset=".034" class="txcmc0bvk"/><stop offset=".131" class="dfwpml94h"/><stop offset=".219" class="aadwvhhqj"/><stop offset=".352" class="kscsed3od"/><stop offset=".605" class="ir1a9obnl"/><stop offset=".719" class="uurw4luby"/><stop offset="1" class="m3nxavbdo"/></linearGradient><linearGradient id="SVGxwNts2ni" x1="16.1" x2="16" y1="28.1" y2="26.9" gradientUnits="userSpaceOnUse"><stop offset=".034" class="txcmc0bvk"/><stop offset=".109" class="dx1z6ocjf"/><stop offset=".219" class="e8vjo1b6d"/><stop offset=".311" class="y70xfzbbt"/><stop offset=".487" class="c03dfbb5s"/><stop offset=".719" class="jxzmprbne"/><stop offset="1" class="m3nxavbdo"/></linearGradient><linearGradient id="SVGkfVWWcEZ" x1="16" x2="15.9" y1="26.5" y2="24.6" href="#SVGxwNts2ni"/><linearGradient id="SVGC5yRKdjZ" x1="16" x2="15.9" y1="25.5" y2="23.4" href="#SVGxwNts2ni"/><linearGradient id="SVGwZi5AdKA" x1="16" x2="15.9" y1="27.6" y2="25.7" href="#SVGxwNts2ni"/><linearGradient id="SVGVT5NieDX" x1="13.7" x2="18.3" y1="28.8" y2="28.8" gradientUnits="userSpaceOnUse"><stop offset=".034" class="gjba8jbgc"/><stop offset=".071" class="t56wp8fan"/><stop offset=".143" class="lrwl6aclg"/><stop offset=".219" class="aadwvhhqj"/><stop offset=".352" class="kscsed3od"/><stop offset=".605" class="ir1a9obnl"/><stop offset=".719" class="uurw4luby"/><stop offset="1" class="xzqchqb_e"/></linearGradient><linearGradient id="SVGqKNtfd4s" x1="12.2" x2="19.5" y1="25.8" y2="25.8" gradientUnits="userSpaceOnUse"><stop offset="0" class="q-kgo_5ib"/><stop offset="0" class="wctzubc1k"/><stop offset=".038" class="o4-2hfb9q"/><stop offset=".112" class="v8sa7q-2s"/><stop offset=".212" class="h12_acbnl"/><stop offset=".264" class="xh1rdac8v"/><stop offset=".303" class="bbxm4bbnf"/><stop offset=".398" class="s6mi-4bco"/><stop offset=".478" class="v7yry5pqd"/><stop offset=".539" class="axlae0bmf"/><stop offset=".573" class="gpjl-mb6u"/><stop offset=".62" class="p0r3ihbyq"/><stop offset=".699" class="hqzl9jbjh"/><stop offset=".8" class="r-bvfbbjs"/><stop offset=".876" class="kioo2ubzl"/><stop offset="1" class="vnxy8lpxj"/><stop offset="1" class="qzac3ebvh"/></linearGradient><linearGradient id="SVGZbcLAiHu" x1="12.2" x2="19.5" y1="24.7" y2="24.7" href="#SVGqKNtfd4s"/><linearGradient id="SVG9yyS1dsu" x1="12.2" x2="19.5" y1="23.5" y2="23.5" href="#SVGqKNtfd4s"/><linearGradient id="SVGiQjece2b" x1="12.2" x2="19.5" y1="26.9" y2="26.9" href="#SVGqKNtfd4s"/><linearGradient id="SVGS9W7scmp" x1="12.2" x2="19.5" y1="26" y2="26" gradientUnits="userSpaceOnUse"><stop offset="0" class="q-kgo_5ib"/><stop offset="0" class="kp6e8ebaw"/><stop offset="0" class="k_c53p4nn"/><stop offset=".036" class="gndn3iwyc"/><stop offset=".105" class="sg1ehcczm"/><stop offset=".199" class="q3ygeerpz"/><stop offset=".264" class="xh1rdac8v"/><stop offset=".303" class="bbxm4bbnf"/><stop offset=".398" class="s6mi-4bco"/><stop offset=".478" class="v7yry5pqd"/><stop offset=".539" class="axlae0bmf"/><stop offset=".573" class="gpjl-mb6u"/><stop offset=".62" class="p0r3ihbyq"/><stop offset=".699" class="hqzl9jbjh"/><stop offset=".8" class="r-bvfbbjs"/><stop offset=".876" class="kioo2ubzl"/><stop offset="1" class="vnxy8lpxj"/><stop offset="1" class="qzac3ebvh"/></linearGradient><linearGradient id="SVG5Yv9LbtS" x1="12.2" x2="19.5" y1="24.9" y2="24.9" href="#SVGS9W7scmp"/><linearGradient id="SVGcHstVcbD" x1="12.2" x2="19.5" y1="27" y2="27" href="#SVGS9W7scmp"/><linearGradient id="SVGAPASgeRT" x1="11.9" x2="19.9" y1="23.2" y2="23.2" href="#SVGxwNts2ni"/><radialGradient id="SVGChvyDe6A" cx="-8.46" cy="-16.6" r="19.4" gradientTransform="translate(34 37.1)scale(1.05)" gradientUnits="userSpaceOnUse"><stop offset=".034" class="w_ni9kbfz"/><stop offset=".112" class="yip_9dbxb"/><stop offset=".219" class="j_xbffdjd"/><stop offset=".408" class="rm_20lbya"/><stop offset=".487" class="oqhxwxdkk"/><stop offset=".544" class="hkcpkwwfd"/><stop offset=".592" class="sfbcvbdfs"/><stop offset=".633" class="n547iqyyz"/><stop offset=".667" class="fr-z_zb1y"/><stop offset=".719" class="ynmma-l5g"/><stop offset="1" class="i7p9jvb8x"/></radialGradient><radialGradient id="SVGFEm3Tdis" cx="-17" cy="-22.9" r="10.7" gradientTransform="translate(34 37.1)scale(1.05)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wuwla16sc"/><stop offset=".505" class="fbeq_z80i"/><stop offset=".568" class="ff3vb3qow"/><stop offset=".664" class="iq011o3fi"/><stop offset=".782" class="rzs6458sd"/><stop offset=".906" class="glec4pwez"/><stop offset="1" class="qttpvibet"/></radialGradient><path id="SVGpHjj2dbG" fill="url(#SVGwZi5AdKA)" class="cur5_obfh"/></defs><path fill="url(#SVGBROSjemU)" class="q_znubb6m"/><path fill="url(#SVGBaHPyczq)" class="rlb078rre"/><path fill="url(#SVGPIrlMdBU)" class="iw_bmb0vy"/><path fill="url(#SVGChvyDe6A)" class="e89suzbnf"/><path fill="url(#SVGxwNts2ni)" class="ojdqasb-y"/><path fill="url(#SVGkfVWWcEZ)" class="k76e-db-w"/><path fill="url(#SVGC5yRKdjZ)" class="jxpyrrgxa"/><use href="#SVGpHjj2dbG"/><use href="#SVGpHjj2dbG"/><path fill="url(#SVGVT5NieDX)" class="spd2ujjyb"/><path fill="url(#SVGqKNtfd4s)" class="jc9b93byx"/><path fill="url(#SVGZbcLAiHu)" class="j4h29z-tv"/><path class="whvdvq9-f"/><path fill="url(#SVG9yyS1dsu)" class="d2a_52ywa"/><path fill="url(#SVGiQjece2b)" class="hu13wgbbb"/><path class="ffdzy7b3s"/><path fill="url(#SVGS9W7scmp)" class="wrk-ubp9s"/><path fill="url(#SVG5Yv9LbtS)" class="d11a39yyk"/><path fill="url(#SVGcHstVcbD)" class="y3t9vwbns"/><path fill="url(#SVGAPASgeRT)" class="yhdn8yc_r"/><path fill="url(#SVGFEm3Tdis)" class="l1jw8ac0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-smarty" /></template>
<style>
.aadwvhhqj {
  stop-color: var(--svg-color--aeb1b8, #aeb1b8);
}

.axlae0bmf {
  stop-color: var(--svg-color--f3f4f5, #f3f4f5);
}

.bbxm4bbnf {
  stop-color: var(--svg-color--636c6f, #636c6f);
}

.c03dfbb5s {
  stop-color: var(--svg-color--84898f, #84898f);
}

.cur5_obfh {
  d: path("M19.439 26.467s.245-.07.245-.163a.1.1 0 0 0-.013-.065a.2.2 0 0 1-.061-.144a.44.44 0 0 1 .119-.27a1 1 0 0 1-.2.1c-.076.028-.245.078-.245.078a25.2 25.2 0 0 1-6.458.436c-.136-.009-.32-.028-.32-.028a1 1 0 0 1-.181-.041a.4.4 0 0 1 .078.217a.72.72 0 0 1-.254.432a.67.67 0 0 1 .368-.079a26.2 26.2 0 0 0 6.922-.473");
}

.d11a39yyk {
  d: path("M12.417 24.8s-.236 0-.241.08s.246.085.246.085s.175 0 .3.005c.619-.012 1.993-.038 3.437-.166c-1.775.07-3.436-.004-3.742-.004");
}

.d2a_52ywa {
  d: path("M19.944 23.034s.041.329-.418.552c-.076.037-.245.1-.245.1a19.4 19.4 0 0 1-6.458.569a8 8 0 0 1-.32-.037c-.276-.05-.467-.209-.455-.4c0 0-.033-.324.466-.324a18.3 18.3 0 0 0 6.925-.461a1 1 0 0 0 .444-.238a.5.5 0 0 1 .061.239");
}

.db7qn2upl {
  stop-color: var(--svg-color--636a6e, #636a6e);
}

.dfwpml94h {
  stop-color: var(--svg-color--a4a5a7, #a4a5a7);
}

.dx1z6ocjf {
  stop-color: var(--svg-color--a5a6a7, #a5a6a7);
}

.e89suzbnf {
  d: path("M19.809 26.838a1 1 0 0 0-.234.389c-.036.181-.1.585-1.326 1.406l-.025.017a.4.4 0 0 1-.086.037a10 10 0 0 1-2.155.209a10 10 0 0 1-2.156-.209a.4.4 0 0 1-.085-.036l-.025-.017a4.6 4.6 0 0 1-1.12-.957c-.164-.219-.373-.257-.39-.345a21 21 0 0 0 3.855.057a13 13 0 0 0 3.761-.654a1 1 0 0 1-.014.103");
}

.e8vjo1b6d {
  stop-color: var(--svg-color--babcc4, #babcc4);
}

.fbeq_z80i {
  stop-color: var(--svg-color--ff0, #ff0);
}

.ff3vb3qow {
  stop-color: var(--svg-color--fdf700, #fdf700);
}

.ffdzy7b3s {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.893 26.576v-.021c-.012.076-.078.236-.417.355c-.076.026-.245.073-.245.073a22.4 22.4 0 0 1-5.1.5a22.2 22.2 0 0 0 5.1-.441s.169-.047.245-.073c.457-.156.417-.393.417-.393m0-3.255V23.3c-.012.076-.078.236-.417.355c-.076.027-.245.073-.245.073a22.4 22.4 0 0 1-5.1.5a22.2 22.2 0 0 0 5.1-.441s.169-.047.245-.073c.457-.156.417-.393.417-.393");
}

.fr-z_zb1y {
  stop-color: var(--svg-color--979ea1, #979ea1);
}

.gjba8jbgc {
  stop-color: var(--svg-color--545453, #545453);
}

.glec4pwez {
  stop-color: var(--svg-color--de9200, #de9200);
}

.gndn3iwyc {
  stop-color: var(--svg-color--c5e4b1, #c5e4b1);
}

.gpjl-mb6u {
  stop-color: var(--svg-color--fefeff, #fefeff);
}

.h12_acbnl {
  stop-color: var(--svg-color--697072, #697072);
}

.hkcpkwwfd {
  stop-color: var(--svg-color--5a5c5f, #5a5c5f);
}

.hqzl9jbjh {
  stop-color: var(--svg-color--dadcdf, #dadcdf);
}

.hu13wgbbb {
  d: path("M19.944 26.586s.041.252-.418.423c-.076.028-.245.078-.245.078a25.2 25.2 0 0 1-6.458.436c-.136-.009-.32-.028-.32-.028c-.276-.038-.467-.16-.455-.308c0 0-.033-.248.466-.248a26.2 26.2 0 0 0 6.925-.472s.245-.07.245-.163a.1.1 0 0 0-.013-.065s.273.161.273.347");
}

.i7p9jvb8x {
  stop-color: var(--svg-color--656c70, #656c70);
}

.i8kc83bgm {
  stop-color: var(--svg-color--636361, #636361);
}

.iq011o3fi {
  stop-color: var(--svg-color--f6e200, #f6e200);
}

.ir1a9obnl {
  stop-color: var(--svg-color--788188, #788188);
}

.iw_bmb0vy {
  d: path("M16 29.8a5 5 0 0 1-.674-.044a1.1 1.1 0 0 0 .674.237h.063a1.1 1.1 0 0 0 .675-.237a5 5 0 0 1-.675.044z");
}

.j_xbffdjd {
  stop-color: var(--svg-color--46474a, #46474a);
}

.j4h29z-tv {
  d: path("M19.944 24.416s.041.252-.418.423c-.076.028-.245.078-.245.078a25.2 25.2 0 0 1-6.458.436c-.136-.009-.32-.028-.32-.028c-.276-.038-.467-.16-.455-.308c0 0-.033-.248.466-.248a26.2 26.2 0 0 0 6.925-.472s.245-.07.245-.162a.1.1 0 0 0-.013-.065s.273.157.273.346");
}

.jc9b93byx {
  d: path("M19.944 25.5s.041.252-.418.423c-.076.028-.245.078-.245.078a25.2 25.2 0 0 1-6.458.436c-.136-.009-.32-.028-.32-.028c-.276-.038-.467-.16-.455-.308c0 0-.033-.249.466-.249a26.2 26.2 0 0 0 6.925-.472s.245-.07.245-.162a.1.1 0 0 0-.013-.066s.273.16.273.348");
}

.jkrnbsmxf {
  stop-color: var(--svg-color--616366, #616366);
}

.jxpyrrgxa {
  d: path("M19.439 24.229s.245-.078.245-.182a.14.14 0 0 0-.013-.073a.25.25 0 0 1-.061-.162a.5.5 0 0 1 .119-.3a1 1 0 0 1-.2.111c-.076.032-.245.088-.245.088a22.5 22.5 0 0 1-6.458.489c-.136-.01-.32-.032-.32-.032a1 1 0 0 1-.181-.046a.46.46 0 0 1 .078.243a.83.83 0 0 1-.254.484a.6.6 0 0 1 .368-.089c.497-.002 4.418.281 6.922-.531");
}

.jxzmprbne {
  stop-color: var(--svg-color--485054, #485054);
}

.k_c53p4nn {
  stop-color: var(--svg-color--d2f3ba, #d2f3ba);
}

.k76e-db-w {
  d: path("M19.439 25.382s.245-.07.245-.162a.1.1 0 0 0-.013-.065a.2.2 0 0 1-.061-.144a.44.44 0 0 1 .119-.27a1 1 0 0 1-.2.1c-.076.028-.245.078-.245.078a25.2 25.2 0 0 1-6.458.436c-.136-.009-.32-.028-.32-.028a1 1 0 0 1-.181-.041a.4.4 0 0 1 .078.217a.72.72 0 0 1-.254.432a.67.67 0 0 1 .368-.079a26.2 26.2 0 0 0 6.922-.474");
}

.kioo2ubzl {
  stop-color: var(--svg-color--8b9298, #8b9298);
}

.kp6e8ebaw {
  stop-color: var(--svg-color--dde8d0, #dde8d0);
}

.kscsed3od {
  stop-color: var(--svg-color--9fa4ab, #9fa4ab);
}

.l1jw8ac0i {
  d: path("M20 22.8a4.5 4.5 0 0 0 .81-1.16a3.4 3.4 0 0 0 .2-1.12a6.7 6.7 0 0 1 .632-2.91c.534-1.01 2.81-4.45 2.81-7.46a8.01 8.01 0 0 0-8.49-8.14a8.01 8.01 0 0 0-8.48 8.14c0 3.02 2.28 6.45 2.81 7.46a6.7 6.7 0 0 1 .632 2.91a3.4 3.4 0 0 0 .2 1.12a4.5 4.5 0 0 0 .81 1.16a13.9 13.9 0 0 0 3.99.37a15.2 15.2 0 0 0 4.08-.369z");
}

.lrwl6aclg {
  stop-color: var(--svg-color--848589, #848589);
}

.m3nxavbdo {
  stop-color: var(--svg-color--8b949a, #8b949a);
}

.n547iqyyz {
  stop-color: var(--svg-color--7f8588, #7f8588);
}

.o-opznbct {
  stop-color: var(--svg-color--6c6d70, #6c6d70);
}

.o4-2hfb9q {
  stop-color: var(--svg-color--ceccc9, #ceccc9);
}

.ojdqasb-y {
  d: path("M19.772 26.88a1 1 0 0 1-.246.129c-.076.028-.245.078-.245.078a25.2 25.2 0 0 1-6.458.436c-.136-.009-.32-.028-.32-.028a1 1 0 0 1-.14-.028a1 1 0 0 1 .14.107c.16.013.319.019.319.019a27 27 0 0 0 6.743-.323l.009-.042a.9.9 0 0 1 .198-.348");
}

.oqhxwxdkk {
  stop-color: var(--svg-color--4e5053, #4e5053);
}

.p0r3ihbyq {
  stop-color: var(--svg-color--f4f5f6, #f4f5f6);
}

.q_znubb6m {
  d: path("M13.859 28.776a.24.24 0 0 0 .128.191a12 12 0 0 0 1.392.622a4 4 0 0 0 .578.072h.052a4 4 0 0 0 .578-.072a12 12 0 0 0 1.392-.622a.24.24 0 0 0 .128-.191l-2.137.192Z");
}

.q-kgo_5ib {
  stop-color: var(--svg-color--e5e1df, #e5e1df);
}

.q3ygeerpz {
  stop-color: var(--svg-color--6e7f71, #6e7f71);
}

.qttpvibet {
  stop-color: var(--svg-color--da9819, #da9819);
}

.qzac3ebvh {
  stop-color: var(--svg-color--a7a9ac, #a7a9ac);
}

.r-bvfbbjs {
  stop-color: var(--svg-color--b0b4b9, #b0b4b9);
}

.rlb078rre {
  d: path("M16.014 30a1.12 1.12 0 0 0 .688-.247a.18.18 0 0 0 .085-.126v-.105a3.2 3.2 0 0 0-.773-.053h-.063a3.2 3.2 0 0 0-.773.053v.105a.18.18 0 0 0 .085.126a1.12 1.12 0 0 0 .688.247Z");
}

.rm_20lbya {
  stop-color: var(--svg-color--48494c, #48494c);
}

.rzs6458sd {
  stop-color: var(--svg-color--ebbf00, #ebbf00);
}

.s6mi-4bco {
  stop-color: var(--svg-color--a5aaac, #a5aaac);
}

.sfbcvbdfs {
  stop-color: var(--svg-color--6a6e71, #6a6e71);
}

.sg1ehcczm {
  stop-color: var(--svg-color--a4bd98, #a4bd98);
}

.spd2ujjyb {
  d: path("M18.224 28.65a.4.4 0 0 1-.086.037a10 10 0 0 1-2.155.209a10 10 0 0 1-2.156-.209a.4.4 0 0 1-.085-.036l-.025-.017l-.029-.019a.1.1 0 0 0 0 .073c.024.073.147.1.147.1a10 10 0 0 0 2.15.209a10 10 0 0 0 2.15-.209s.126-.029.147-.1a.12.12 0 0 0 0-.073l-.029.019Z");
}

.sqeir4bkd {
  stop-color: var(--svg-color--010101, #010101);
}

.t56wp8fan {
  stop-color: var(--svg-color--616262, #616262);
}

.txcmc0bvk {
  stop-color: var(--svg-color--9b9b98, #9b9b98);
}

.uaxk0gb2x {
  stop-color: var(--svg-color--3c3d3f, #3c3d3f);
}

.uurw4luby {
  stop-color: var(--svg-color--657076, #657076);
}

.v7yry5pqd {
  stop-color: var(--svg-color--d5d7d9, #d5d7d9);
}

.v8sa7q-2s {
  stop-color: var(--svg-color--a7a9a8, #a7a9a8);
}

.vnxy8lpxj {
  stop-color: var(--svg-color--d1d3d4, #d1d3d4);
}

.w_ni9kbfz {
  stop-color: var(--svg-color--70706e, #70706e);
}

.wc64txvkk {
  stop-color: var(--svg-color--6f7175, #6f7175);
}

.wctzubc1k {
  stop-color: var(--svg-color--dddad6, #dddad6);
}

.whvdvq9-f {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.893 24.406v-.021c-.012.076-.078.236-.417.355c-.076.026-.245.073-.245.073a22.4 22.4 0 0 1-5.1.5a22.2 22.2 0 0 0 5.1-.441s.169-.047.245-.073c.457-.156.417-.393.417-.393m0 1.085v-.021c-.012.076-.078.236-.417.355c-.076.027-.245.073-.245.073a22.4 22.4 0 0 1-5.1.5a22.2 22.2 0 0 0 5.1-.441s.169-.047.245-.073c.457-.156.417-.393.417-.393");
}

.wrk-ubp9s {
  d: path("M12.417 25.881s-.236 0-.241.08s.246.085.246.085s.175 0 .3.005c.619-.013 1.993-.038 3.437-.166c-1.775.073-3.436-.002-3.742-.004");
}

.wuwla16sc {
  stop-color: var(--svg-color--ffffd1, #ffffd1);
}

.xh1rdac8v {
  stop-color: var(--svg-color--465054, #465054);
}

.xzqchqb_e {
  stop-color: var(--svg-color--505659, #505659);
}

.y3t9vwbns {
  d: path("M12.417 26.965s-.236 0-.241.08s.246.085.246.085s.175 0 .3.005c.619-.012 1.993-.038 3.437-.166c-1.775.073-3.436-.003-3.742-.004");
}

.y70xfzbbt {
  stop-color: var(--svg-color--abaeb5, #abaeb5);
}

.yhdn8yc_r {
  d: path("M12 22.8s-.274.315.319.711c0 0 5.78.587 7.6-.695c0 0-6.26.525-7.92-.016z");
}

.yip_9dbxb {
  stop-color: var(--svg-color--616261, #616261);
}

.ynmma-l5g {
  stop-color: var(--svg-color--3d4447, #3d4447);
}

</style>
