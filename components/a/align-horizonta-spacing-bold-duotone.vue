<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rotba7baa"/><path class="c52h3c0el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizonta-spacing-bold-duotone" /></template>
<style>
.c52h3c0el {
  fill: currentColor;
  d: path("M12 20c1.886 0 2.828 0 3.414-.586S16 17.886 16 16V8c0-1.886 0-2.828-.586-3.414S13.886 4 12 4s-2.828 0-3.414.586S8 6.114 8 8v8c0 1.886 0 2.828.586 3.414S10.114 20 12 20");
}

.rotba7baa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 22.75a.75.75 0 0 1-.75-.75V2a.75.75 0 0 1 1.5 0v20a.75.75 0 0 1-.75.75m-18 0a.75.75 0 0 1-.75-.75V2a.75.75 0 0 1 1.5 0v20a.75.75 0 0 1-.75.75");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
