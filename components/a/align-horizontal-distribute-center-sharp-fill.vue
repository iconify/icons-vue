<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsqknw_do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-distribute-center-sharp-fill" /></template>
<style>
.gsqknw_do {
  fill: currentColor;
  d: path("M8 1V4H10C10.552 4 11 4.448 11 5V19C11 19.552 10.552 20 10 20H8V23H6V20H4C3.448 20 3 19.552 3 19V5C3 4.448 3.448 4 4 4H6V1H8ZM18 1V6H20C20.552 6 21 6.448 21 7V17C21 17.552 20.552 18 20 18H18V23H16V18H14C13.448 18 13 17.552 13 17V7C13 6.448 13.448 6 14 6H16V1H18Z");
}

</style>
