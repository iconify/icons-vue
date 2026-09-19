<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="azjiubb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-n" /></template>
<style>
.azjiubb1n {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m11.762 44.508h-6.061L25.889 25.92v20.588h-5.65V17.492h6.357l11.518 20.231V17.492h5.648z");
}

</style>
