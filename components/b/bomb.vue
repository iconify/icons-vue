<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xa09imbpg"/><circle class="o51vz5b-u"/><path class="e084ypb1t"/><circle class="xoo_yfbqa"/><circle class="gkv51tkse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bomb" /></template>
<style>
.e084ypb1t {
  fill: var(--svg-color--31373d, #31373d);
  d: path("m19 11.342l5.658-5.657l5.657 5.658L24.657 17z");
}

.gkv51tkse {
  cx: 32px;
  cy: 4px;
  r: 2px;
  fill: var(--svg-color--fdcb58, #fdcb58);
}

.o51vz5b-u {
  cx: 14px;
  cy: 22px;
  r: 14px;
  fill: var(--svg-color--31373d, #31373d);
}

.xa09imbpg {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m24.187 9.657l5.658-5.654L32 6.16l-5.658 5.655z");
}

.xoo_yfbqa {
  cx: 32px;
  cy: 4px;
  r: 4px;
  fill: var(--svg-color--f18f26, #f18f26);
}

</style>
