<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="khy2wqb3t"/><path class="cb1chybwy"/><path class="djbfv_bof"/><path class="xfgplxboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-st-vincent-and-grenadines" /></template>
<style>
.cb1chybwy {
  fill: var(--svg-color--0072c6, #0072c6);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h5V5z");
}

.djbfv_bof {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M9 5h18v26H9z");
}

.khy2wqb3t {
  fill: var(--svg-color--009e60, #009e60);
  d: path("M32 5h-5v26h5a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.xfgplxboz {
  fill: var(--svg-color--009e60, #009e60);
  d: path("M15.833 23.526L18 27.859l2.167-4.333L18 19.193zm-2.708-5.417l2.167 4.333l2.167-4.333l-2.167-4.333zm5.417 0l2.167 4.333l2.167-4.333l-2.167-4.333z");
}

</style>
