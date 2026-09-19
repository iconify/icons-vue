<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="laov0p_-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-chile" /></template>
<style>
.laov0p_-f {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M18.385 16.513L20.2 11.35l1.87 5.163h5.996l-4.84 3.352l1.836 5.253l-4.862-3.229l-4.862 3.229l1.836-5.253l-4.84-3.352zM4 31v-2h28V4c15.104 0 27.471 12.022 28 27z");
}

</style>
