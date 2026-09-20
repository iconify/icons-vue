<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="btnnu3b4e"/><circle class="uqkidhbid"/><circle class="t3a1mi49j"/><circle class="r9dsrlegt"/><circle class="ca-7brbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:artist-palette" /></template>
<style>
.btnnu3b4e {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M18 3.143c-9.941 0-18 6.908-18 15.428c0 1.066.126 2.107.367 3.112C2.146 24.744 3.377 22.812 9 20c5.727-2.864 0 4-2 8c-.615 1.23-.282 2.271.56 3.124C10.506 32.928 14.104 34 18 34c9.941 0 18-6.907 18-15.429c0-8.52-8.059-15.428-18-15.428m2.849 24.447c-.395 1.346-2.46 1.924-4.613 1.291c-2.153-.632-3.578-2.234-3.183-3.581s2.46-1.924 4.613-1.29c2.153.631 3.578 2.233 3.183 3.58");
}

.ca-7brbpz {
  cx: 28px;
  cy: 24px;
  r: 3px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.r9dsrlegt {
  cx: 29px;
  cy: 15px;
  r: 3px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.t3a1mi49j {
  cx: 20px;
  cy: 9px;
  r: 3px;
  fill: var(--svg-color--269, #269);
}

.uqkidhbid {
  cx: 10px;
  cy: 11px;
  r: 3px;
  fill: var(--svg-color--5c913b, #5c913b);
}

</style>
