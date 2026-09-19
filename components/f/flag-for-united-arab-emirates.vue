<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hwk5csx9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-united-arab-emirates" /></template>
<style>
.hwk5csx9o {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m-9 40v16.564a28 28 0 0 1-2-.746V6.182c.653-.275 1.322-.52 2-.746V22h35.213C59.365 25.062 60 28.541 60 32s-.635 6.938-1.787 10z");
}

</style>
