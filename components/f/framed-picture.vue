<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u15zq2b1m"/><path class="w-9lsxbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:framed-picture" /></template>
<style>
.u15zq2b1m {
  fill: currentColor;
  d: path("M49 34.446V17H15v30h34zM41.999 20a4 4 0 1 1 .003 8a4 4 0 0 1-.003-8m-9.171 9.683l8.653 8.064l-8.653 2.606zm14.66 15.985H16.512V34.446h7.614l-4.177 3.893l12.124 3.652l12.124-3.652l-4.178-3.893h7.469zM31.317 29.683v10.671l-8.652-2.606z");
}

.w-9lsxbhi {
  fill: currentColor;
  d: path("M2 4v56h60V4zm51 47H11V13h42z");
}

</style>
