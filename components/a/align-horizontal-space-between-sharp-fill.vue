<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdxy1xm5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-between-sharp-fill" /></template>
<style>
.tdxy1xm5a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 6H9C9.552 6 10 6.4477 10 7V17C10 17.5523 9.552 18 9 18H5V23H3V1H5V6ZM19 6H15C14.448 6 14 6.4477 14 7V17C14 17.5523 14.448 18 15 18H19V23H21V1H19V6Z");
}

</style>
