<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1ar9lkuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-angry-sharp" /></template>
<style>
.c1ar9lkuc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12ZM7.7071 8.7071L10.2929 11.2929M16.2929 8.7071L13.7071 11.2929M8.7071 17.2929L9 17C10 16 11 15.5 12 15.5C13 15.5 14 16 15 17L15.2929 17.2929");
}

</style>
