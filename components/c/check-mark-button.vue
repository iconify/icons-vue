<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dcryse_3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:check-mark-button" /></template>
<style>
.dcryse_3g {
  fill: currentColor;
  d: path("M32 2C15.431 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m-6.975 48l-.02-.02l-.017.02L11 35.6l7.029-7.164l6.977 7.184l21-21.619L53 21.199z");
}

</style>
