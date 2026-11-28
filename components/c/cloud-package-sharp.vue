<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb4qo3bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-package-sharp" /></template>
<style>
.lb4qo3bkg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.738L17 14.118L17 18.618L12 20.998L7 18.618L7 14.118ZM7.0024 14.1374L12 16.618L16.9976 14.1374M12 16.618L12 21M3.2986 15.9844L3 15.6458C2.3556 14.915 2 13.9743 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 13.9743 21.6444 14.915 21 15.6458L20.7014 15.9844");
}

</style>
