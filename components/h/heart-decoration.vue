<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kssnc_6tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:heart-decoration" /></template>
<style>
.kssnc_6tj {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 48c-1.371-1.814-20.53-12.883-16.602-25.218c3.53-11.073 15.094-6.597 16.602-.594c1.094-5.635 12.949-10.694 16.604.584C52.529 36.908 33.367 48.557 32 50");
}

</style>
