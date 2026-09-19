<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d8cpqnqrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-bahrain" /></template>
<style>
.d8cpqnqrk {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M4 32C4 17.61 14.912 5.727 28.895 4.176L35.934 8.4L26.1 14.3l9.833 5.9l-9.833 5.9l9.833 5.9l-9.833 5.9l9.833 5.899L26.1 49.7l9.833 5.899l-7.042 4.224C14.911 58.271 4 46.389 4 32");
}

</style>
