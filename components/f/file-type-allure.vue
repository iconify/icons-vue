<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<linearGradient id="SVGv7eHAeTx" x1="26.4" x2="28.8" y1="9.6" y2="15" gradientUnits="userSpaceOnUse"><stop class="zov-qnpum"/><stop offset="1" class="z-wj5t2su"/></linearGradient><linearGradient id="SVGMQXW5cOZ" x1="26.8" x2="17.8" y1="9.4" y2="3.6" href="#SVGv7eHAeTx"><stop class="olw50kbdx"/><stop offset="1" class="jwwb_xbwf"/></linearGradient><linearGradient id="SVG7lPwrdsi" x1="3.6" x2="5.4" y1="14" y2="24.8" href="#SVGv7eHAeTx"><stop class="xh53xjbng"/><stop offset="1" class="zj-hb0bfs"/></linearGradient><linearGradient id="SVGyNYrcdaY" x1="4.8" x2="14.4" y1="22.2" y2="29.2" href="#SVGv7eHAeTx"><stop class="ykjfm24il"/><stop offset=".96" class="lhkv0xzfh"/></linearGradient><linearGradient id="SVGqiFWIddi" x1="28.4" x2="22.2" y1="22.2" y2="28.4" href="#SVGv7eHAeTx"><stop class="anh21-u6s"/><stop offset="1" class="ykd9cjbnf"/></linearGradient><clipPath id="SVGh4epsdyo"><path class="dqjyn2bld"/></clipPath><clipPath id="SVGseksXbjI"><path class="yheihnbxw"/></clipPath><g clip-path="url(#SVGseksXbjI)" transform="matrix(.8 0 0 .8 3.2 3.2)"><path id="SVGzMVxV9Tm" fill="url(#SVGv7eHAeTx)" class="ls2p0b3cp"/><path fill="url(#SVGMQXW5cOZ)" class="nf8bbrdma"/><path fill="url(#SVG7lPwrdsi)" class="qt86564ko"/><path fill="url(#SVGyNYrcdaY)" class="ul8whyjnk"/><path fill="url(#SVGqiFWIddi)" class="tdrb0pucy"/><path class="c69pngbaq"/><use clip-path="url(#SVGh4epsdyo)" href="#SVGzMVxV9Tm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-allure" /></template>
<style>
.anh21-u6s {
  stop-color: var(--svg-color--d97706, #d97706);
}

.c69pngbaq {
  fill: var(--svg-color--fbbf24, #fbbf24);
  d: path("M28.38 12.4a3.6 3.6 0 0 1 3.6 3.6v12.4a3.6 3.6 0 1 1-7.2 0V16a3.6 3.6 0 0 1 3.6-3.6");
}

.dqjyn2bld {
  d: path("M24.8 12H32v8h-7.2z");
}

.jwwb_xbwf {
  stop-color: var(--svg-color--dc2626, #dc2626);
}

.lhkv0xzfh {
  stop-color: var(--svg-color--64748b, #64748b);
}

.ls2p0b3cp {
  d: path("M22.23 4.66a3.6 3.6 0 0 1 5.1.04A16 16 0 0 1 31.97 16a3.6 3.6 0 1 1-7.2 0a9 9 0 0 0-2.58-6.24a3.6 3.6 0 0 1 .03-5.1z");
}

.nf8bbrdma {
  d: path("M12.4 3.6A3.6 3.6 0 0 1 16 0c4.4 0 8.4 1.8 11.29 4.66a3.6 3.6 0 0 1-5.06 5.13A9 9 0 0 0 16 7.2a3.6 3.6 0 0 1-3.6-3.6");
}

.olw50kbdx {
  stop-color: var(--svg-color--ef4444, #ef4444);
}

.qt86564ko {
  d: path("M0 16A16 16 0 0 1 16 0a3.6 3.6 0 0 1 0 7.2a8.8 8.8 0 0 0-6.21 15.04a3.6 3.6 0 0 1-5.13 5.06A16 16 0 0 1 0 16");
}

.tdrb0pucy {
  d: path("M28.38 12.4a3.6 3.6 0 0 1 3.6 3.6A16 16 0 0 1 16 32a3.6 3.6 0 0 1 0-7.2a8.8 8.8 0 0 0 8.8-8.8a3.6 3.6 0 0 1 3.6-3.6z");
}

.ul8whyjnk {
  d: path("M4.66 22.24a3.6 3.6 0 0 1 5.1-.03a9 9 0 0 0 6.23 2.59a3.6 3.6 0 0 1 0 7.2c-4.4 0-8.4-1.8-11.3-4.66a3.6 3.6 0 0 1-.03-5.1");
}

.xh53xjbng {
  stop-color: var(--svg-color--22c55e, #22c55e);
}

.yheihnbxw {
  d: path("M0 0h32v32H0z");
}

.ykd9cjbnf {
  stop-color: var(--svg-color--fbbf24, #fbbf24);
}

.ykjfm24il {
  stop-color: var(--svg-color--94a3b8, #94a3b8);
}

.z-wj5t2su {
  stop-color: var(--svg-color--8b5cf6, #8b5cf6);
}

.zj-hb0bfs {
  stop-color: var(--svg-color--15803d, #15803d);
}

.zov-qnpum {
  stop-color: var(--svg-color--7e22ce, #7e22ce);
}

</style>
