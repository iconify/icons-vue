<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tm99dfc3e"/><path class="cvyd4hdhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-down-bold-duotone" /></template>
<style>
.cvyd4hdhk {
  fill: currentColor;
  d: path("M18.5303 6.53033C18.8232 6.23744 18.8232 5.76256 18.5303 5.46967C18.2374 5.17678 17.7626 5.17678 17.4697 5.46967L10.5 12.4393L11.5607 13.5L18.5303 6.53033Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tm99dfc3e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5607 13.5L10.5 12.4393L6.53033 8.46966C6.31583 8.25516 5.99324 8.191 5.71299 8.30708C5.43273 8.42317 5.25 8.69664 5.25 8.99999V18C5.25 18.4142 5.58579 18.75 6 18.75L15 18.75C15.3033 18.75 15.5768 18.5673 15.6929 18.287C15.809 18.0068 15.7448 17.6842 15.5303 17.4697L11.5607 13.5Z");
}

</style>
