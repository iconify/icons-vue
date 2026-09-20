<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGaRxOLdYe"><stop offset=".15" class="b6r6x2k9z"/><stop offset=".39" class="yoj2x5unv"/><stop offset="1" class="m_ik79n2s"/></linearGradient><linearGradient id="SVGsG9qJbtn"><stop offset="0" class="ho413kbqm"/><stop offset="1" class="e2e82nbve"/></linearGradient><linearGradient id="SVGBu3X2bSJ"><stop offset="0" class="ho413kbqm"/><stop offset="1" class="yagxylmfe"/></linearGradient><clipPath id="SVGqpIVPcCN"><path class="ang0-8bkx"/></clipPath></defs><g clip-path="url(#SVGqpIVPcCN)" transform="translate(2.76 1.986)scale(.11923)"><path fill="url(#SVGsG9qJbtn)" class="lzmzk1bgq"/><path fill="url(#SVGBu3X2bSJ)" class="lzmzk1bgq"/></g><path fill="url(#SVGaRxOLdYe)" class="vbeq02bbb"/><path class="cm2faab-o"/><path class="r5zh_hdsc"/><path class="cdijtsbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ng-component-less" /></template>
<style>
.ang0-8bkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h223v236H0z");
}

.b6r6x2k9z {
  stop-color: var(--svg-color--2a4f84, #2a4f84);
}

.cdijtsbmy {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  d: path("M13.87 26.59h-.25c-.28 0-.38-.14-.38-.44v-5.34a1 1 0 0 0-.21-.68c-.12-.13-.33-.13-.63-.13h-.64v6.42a1.48 1.48 0 0 0 .28 1a1.14 1.14 0 0 0 .91.31a6 6 0 0 0 1-.09a1.8 1.8 0 0 0 0-.4a1.8 1.8 0 0 0-.11-.62Z");
}

.cm2faab-o {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  d: path("M25.6 24.79a1.56 1.56 0 0 1 1.25 1.5a1.34 1.34 0 0 1-.52 1.11a2.32 2.32 0 0 1-1.47.44a3.6 3.6 0 0 1-1.77-.49a1.6 1.6 0 0 1 .13-.53a1.5 1.5 0 0 1 .28-.46a2.9 2.9 0 0 0 1.31.39a.76.76 0 0 0 .4-.09a.27.27 0 0 0 .14-.24q0-.28-.43-.42l-.52-.2q-1.17-.43-1.17-1.39a1.39 1.39 0 0 1 .49-1.12a2 2 0 0 1 1.28-.51a4 4 0 0 1 .91.12a3.6 3.6 0 0 1 .82.37a1.3 1.3 0 0 1-.1.57a1 1 0 0 1-.3.44a3.4 3.4 0 0 0-1.33-.35a.43.43 0 0 0-.29.08a.27.27 0 0 0-.1.21q0 .22.36.35l.58.21Zm-4.16 0a1.56 1.56 0 0 1 1.25 1.5a1.34 1.34 0 0 1-.52 1.11a2.33 2.33 0 0 1-1.47.44a3.6 3.6 0 0 1-1.77-.49a1.6 1.6 0 0 1 .13-.53a1.4 1.4 0 0 1 .28-.46a2.9 2.9 0 0 0 1.31.39a.76.76 0 0 0 .4-.09a.27.27 0 0 0 .14-.24q0-.28-.43-.42l-.52-.2q-1.17-.43-1.17-1.39a1.39 1.39 0 0 1 .49-1.12a2 2 0 0 1 1.33-.51a4 4 0 0 1 .91.12a3.6 3.6 0 0 1 .82.37a1.3 1.3 0 0 1-.1.57a1 1 0 0 1-.3.44a3.4 3.4 0 0 0-1.31-.35a.43.43 0 0 0-.29.08a.27.27 0 0 0-.1.21q0 .22.36.35Zm-3.04.06a2.2 2.2 0 0 0-.14-.79a1.8 1.8 0 0 0-.39-.62a1.8 1.8 0 0 0-.62-.41a2.2 2.2 0 0 0-.81-.25a2.2 2.2 0 0 0-.93.29a1.8 1.8 0 0 0-.66.51a2.2 2.2 0 0 0-.39.77a3.5 3.5 0 0 0-.13 1a4.5 4.5 0 0 0 .1 1a2.1 2.1 0 0 0 .35.79a1.7 1.7 0 0 0 .65.52a2.3 2.3 0 0 0 1 .22a3.13 3.13 0 0 0 1.84-.56a1.48 1.48 0 0 0-.38-.86a5 5 0 0 1-.68.21a2.5 2.5 0 0 1-.52.06a.81.81 0 0 1-.65-.23a.94.94 0 0 1-.21-.61h2.44a3.5 3.5 0 0 0 .13-1.04m-2.57.06a1.9 1.9 0 0 1 .17-.79a.5.5 0 0 1 .44-.21a.52.52 0 0 1 .46.22a1.4 1.4 0 0 1 .15.68v.1Z");
}

.e2e82nbve {
  stop-color: var(--svg-color--b13138, #b13138);
}

.ho413kbqm {
  stop-color: var(--svg-color--de3641, #de3641);
}

.lzmzk1bgq {
  d: path("m222.08 39.192l-8.019 125.92L137.39-.008zm-53.105 162.82l-57.933 33.056l-57.934-33.056l11.783-28.556h92.301zm-57.933-139.34l30.357 73.803H80.684zm-103.1 102.44L.005 39.192L84.695 0z");
}

.m_ik79n2s {
  stop-color: var(--svg-color--172e4e, #172e4e);
}

.r5zh_hdsc {
  fill: var(--svg-color--f6f6f6, #f6f6f6);
  stroke: var(--svg-color--404040, #404040);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M29.42 25.54a1.27 1.27 0 0 0-.42 1v1.62a1.43 1.43 0 0 1-.54 1.23a2.22 2.22 0 0 1-1.31.43h-.3V29a1 1 0 0 0 .47-.26a1.08 1.08 0 0 0 .33-.83v-1.3a2 2 0 0 1 .2-1a2 2 0 0 1 1-.66a2 2 0 0 1-1-.93a2.3 2.3 0 0 1-.11-.92v-1.2a1.15 1.15 0 0 0-.29-.83a.9.9 0 0 0-.51-.25V20h.73a1.33 1.33 0 0 1 .81.35a1.6 1.6 0 0 1 .53.8a1.8 1.8 0 0 1 .07.55v1.4a1.46 1.46 0 0 0 .4 1.09a1.7 1.7 0 0 0 .68.38v.63a1.54 1.54 0 0 0-.65.34ZM10.75 20h-.26a1.32 1.32 0 0 0-.81.35a1.35 1.35 0 0 0-.53.8a3 3 0 0 0 0 .55v1.4a1.48 1.48 0 0 1-.43 1.1a2.3 2.3 0 0 1-.78.38v.63a2 2 0 0 1 .75.34a1.3 1.3 0 0 1 .46 1v1.62a1.41 1.41 0 0 0 .5 1.23a2.22 2.22 0 0 0 1.31.44h.33V29a1.16 1.16 0 0 1-.51-.26a1.07 1.07 0 0 1-.29-.83v-1.29a2 2 0 0 0-.24-1a2 2 0 0 0-1-.66a2 2 0 0 0 1-.93a2.3 2.3 0 0 0 .14-.92v-1.2a1.16 1.16 0 0 1 .31-.91a1 1 0 0 1 .46-.21h.34V20Z");
}

.vbeq02bbb {
  d: path("M28.93 27.94a1.9 1.9 0 0 1-1.9 1.9H11.1a1.9 1.9 0 0 1-1.9-1.9v-6A1.9 1.9 0 0 1 11.06 20H27a1.9 1.9 0 0 1 1.9 1.9Z");
}

.yagxylmfe {
  stop-color: var(--svg-color--de3641, #de3641);
  stop-opacity: 0;
}

.yoj2x5unv {
  stop-color: var(--svg-color--294e82, #294e82);
}

</style>
