<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG4R6kCdHa)" class="w3b6s1b4j"/><defs><linearGradient id="SVG4R6kCdHa" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="ddp7g1z1f"/><stop offset="1" class="zew71i4ui"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lsd" /></template>
<style>
.ddp7g1z1f {
  stop-color: var(--svg-color--6f76fb, #6f76fb);
}

.ft5dv1b6b {
  fill: none;
}

.w3b6s1b4j {
  d: path("M18.924 21c-3.234-3.611-5.31-5.063-7.2-5.063c-1.67 0-3.206 1.16-5.27 2.813l-.979-1.125C8.462 12.73 6.808 10.442 3.844 6.43l.973-1.181C9.58 8.231 13.018 9.671 17.867 3l1.204.832c-1.199 2.655-1.66 4.85-1.632 6.92c.04 3.037 1.215 5.804 2.717 9.365z");
}

.zew71i4ui {
  stop-color: var(--svg-color--2730ec, #2730ec);
}

</style>
