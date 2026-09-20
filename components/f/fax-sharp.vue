<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm2-ncjsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fax-sharp" /></template>
<style>
.rm2-ncjsp {
  fill: currentColor;
  d: path("M8 20V4h10v5h4v11zm-6 1h5V8H2zm8-12h6V6h-6zm0 8h4v-5h-4zm5-3h2v-2h-2zm3 0h2v-2h-2zm-3 3h2v-2h-2zm3 0h2v-2h-2z");
}

</style>
