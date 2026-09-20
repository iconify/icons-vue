<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG1GRd7dST" x1="36.036" x2="171.04" y1="171.21" y2="36.209" gradientTransform="translate(-93.833 -117.64)scale(1.2523)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sezni-qdc"/><stop offset=".495" class="vi6-wh6hx"/><stop offset="1" class="xxsilqbjg"/></linearGradient></defs><path fill="url(#SVG1GRd7dST)" clip-rule="evenodd" transform="translate(10.022 13.873)scale(.16512)" class="plyduhb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-shuttle" /></template>
<style>
.plyduhb4u {
  fill-rule: evenodd;
  d: path("M78.693-71.892L36.408-29.608H-5.876L-48.16 12.675h42.284V54.96H-48.16v42.284h42.284V54.96h42.284v42.284L78.693 54.96V12.675l42.284-42.283v-42.284z");
}

.sezni-qdc {
  stop-color: var(--svg-color--f42929, #f42929);
}

.vi6-wh6hx {
  stop-color: var(--svg-color--ff8a3f, #ff8a3f);
}

.xxsilqbjg {
  stop-color: var(--svg-color--e5e938, #e5e938);
}

</style>
