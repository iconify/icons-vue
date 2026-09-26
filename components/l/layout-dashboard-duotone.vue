<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfbi1bblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layout-dashboard-duotone" /></template>
<style>
.sfbi1bblv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3H9C9.55228 3 10 3.44772 10 4V11C10 11.55228 9.55228 12 9 12H4C3.44772 12 3 11.55228 3 11V4C3 3.44772 3.44772 3 4 3ZM4 16H9C9.55228 16 10 16.44772 10 17V20C10 20.55228 9.55228 21 9 21H4C3.44772 21 3 20.55228 3 20V17C3 16.44772 3.44772 16 4 16ZM15 3H20C20.55228 3 21 3.44772 21 4V7C21 7.55228 20.55228 8 20 8H15C14.44772 8 14 7.55228 14 7V4C14 3.44772 14.44772 3 15 3ZM15 12H20C20.55228 12 21 12.44772 21 13V20C21 20.55228 20.55228 21 20 21H15C14.44772 21 14 20.55228 14 20V13C14 12.44772 14.44772 12 15 12Z");
}

</style>
