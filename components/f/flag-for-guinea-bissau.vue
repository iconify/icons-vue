<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ryc798h0i"/><path class="e8hx7o-3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-guinea-bissau" /></template>
<style>
.e8hx7o-3r {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M21.167 57.818C11.091 53.574 4 43.601 4 32s7.091-21.574 17.167-25.818zm2-26.818V5.436A27.9 27.9 0 0 1 32 4c15.104 0 27.445 12.022 27.975 27z");
}

.ryc798h0i {
  fill: currentColor;
  d: path("m6.434 30.279l4.234 3.352l-1.604 5.253l4.252-3.231l4.251 3.231l-1.602-5.253l4.235-3.352h-5.249l-1.635-5.162l-1.587 5.162z");
}

</style>
