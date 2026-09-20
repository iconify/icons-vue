<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="komtombne"/><path class="g_9re3uap"/><path class="jsq7yzb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lith" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g_9re3uap {
  fill: var(--svg-color--e96036, #e96036);
  d: path("M17.464 10.072a3.536 3.536 0 1 0 0-7.072a3.536 3.536 0 0 0 0 7.072");
}

.jsq7yzb3y {
  fill: var(--svg-color--000, #000);
  d: path("M6.536 21a3.536 3.536 0 1 0 0-7.071a3.536 3.536 0 0 0 0 7.071m10.928 0a3.536 3.536 0 1 0 0-7.071a3.536 3.536 0 0 0 0 7.071");
}

.komtombne {
  fill: var(--svg-color--000, #000);
  d: path("M6.536 10.072a3.536 3.536 0 1 0 0-7.072a3.536 3.536 0 0 0 0 7.072");
}

</style>
