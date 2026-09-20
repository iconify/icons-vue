<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":231};
const content = `<defs><linearGradient id="SVGR9diIphF" x1="108.633%" x2="46.927%" y1="13.818%" y2="78.776%"><stop offset="18%" class="sav6x4bmf"/><stop offset="100%" class="g_gp7lgqe"/></linearGradient></defs><g class="ft5dv1b6b"><path class="blup_rbdn"/><path class="ocq9b2bbi"/><path fill="url(#SVGR9diIphF)" class="d7-417bsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bitbucket" /></template>
<style>
.blup_rbdn {
  d: path("M101.272 152.561h53.449l12.901-75.319H87.06z");
}

.d7-417bsq {
  d: path("M244.61 77.242h-76.916l-12.909 75.36h-53.272l-62.902 74.663a11.1 11.1 0 0 0 7.171 2.704H212.73a8.196 8.196 0 0 0 8.196-6.884z");
}

.ft5dv1b6b {
  fill: none;
}

.g_gp7lgqe {
  stop-color: var(--svg-color--2684ff, #2684ff);
}

.ocq9b2bbi {
  fill: var(--svg-color--2684ff, #2684ff);
  d: path("M8.308 0A8.202 8.202 0 0 0 .106 9.516l34.819 211.373a11.155 11.155 0 0 0 10.909 9.31h167.04a8.2 8.2 0 0 0 8.201-6.89l34.82-213.752a8.202 8.202 0 0 0-8.203-9.514zm146.616 152.768h-53.315l-14.436-75.42h80.67z");
}

.sav6x4bmf {
  stop-color: var(--svg-color--0052cc, #0052cc);
}

</style>
