<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6asd5bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sync" /></template>
<style>
.k6asd5bgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 16.5C16.5 18.9853 14.4853 21 12 21C9.5147 21 7.5 18.9853 7.5 16.5C7.5 14.0147 9.5147 12 12 12H14M11.4645 9L14.6464 11.6464C14.8417 11.8417 14.8417 12.1583 14.6464 12.3536L11.4645 15.5355M3.4925 16.1166C2.5573 15.3644 2 14.2219 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.229 21.4361 15.3777 20.4911 16.1297");
}

</style>
