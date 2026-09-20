<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="pt-3kkb2k"/><path class="wluwrgbwr"/><path class="ok4hljnpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-spreadsheet-outline-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.ok4hljnpw {
  d: path("M12 9v8.5");
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wluwrgbwr {
  d: path("M9 14.5h6");
}

</style>
