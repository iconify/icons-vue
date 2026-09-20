<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":238};
const content = `<defs><linearGradient id="SVGjzk6ueva" x1="86.924%" x2="7.63%" y1="94.294%" y2="45.952%"><stop offset="9%" class="ovzu8acsw"/><stop offset="100%" class="s5swet9dp"/></linearGradient><linearGradient id="SVGb0f7AcFJ" x1="99.538%" x2="23.437%" y1="93.901%" y2="54.033%"><stop offset="15%" class="brbf7obdx"/><stop offset="33%" class="e7jf3cplj"/><stop offset="48%" class="h_b_e_04y"/></linearGradient><linearGradient id="SVGxMwz6dYk" x1="87.128%" x2="-.639%" y1="51.518%" y2="93.078%"><stop offset="55%" class="vtv1nccpp"/><stop offset="85%" class="fwf08fblg"/></linearGradient><path id="SVGAiIt3btS" class="r8qiucakw"/></defs><mask id="SVG6FLXsceq" class="n1mjunbsu"><use href="#SVGAiIt3btS"/></mask><g mask="url(#SVG6FLXsceq)"><path fill="url(#SVGjzk6ueva)" transform="translate(-42.87 -58.67)" class="jf9t4ac7m"/><path fill="url(#SVGb0f7AcFJ)" transform="translate(-42.87 -58.67)" class="n6w1kmbet"/><path fill="url(#SVGxMwz6dYk)" transform="translate(-42.87 -58.67)" class="o-js4ybmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-drive" /></template>
<style>
.brbf7obdx {
  stop-color: var(--svg-color--a9a8ff, #a9a8ff);
}

.e7jf3cplj {
  stop-color: var(--svg-color--6d97ff, #6d97ff);
}

.fwf08fblg {
  stop-color: var(--svg-color--78c9ff, #78c9ff);
}

.h_b_e_04y {
  stop-color: var(--svg-color--3186ff, #3186ff);
}

.jf9t4ac7m {
  d: path("M341.719 295.937H200.166l-29.293-50.735l70.777-122.589z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n6w1kmbet {
  d: path("m0 295.916l100.069-173.325v.003l-29.282 50.723h58.57l70.783 122.596l-200.138.001z");
}

.o-js4ybmo {
  d: path("m170.881 0l70.781 122.6l-29.286 50.726H70.812z");
}

.ovzu8acsw {
  stop-color: var(--svg-color--ffe921, #ffe921);
}

.r8qiucakw {
  d: path("M77.303 29.27c22.531-39.026 78.863-39.027 101.394 0l69.373 120.158c22.531 39.027-5.633 87.81-50.698 87.81H58.628c-45.065 0-73.23-48.783-50.698-87.81z");
}

.s5swet9dp {
  stop-color: var(--svg-color--fec700, #fec700);
}

.vtv1nccpp {
  stop-color: var(--svg-color--0ebc5f, #0ebc5f);
}

</style>
