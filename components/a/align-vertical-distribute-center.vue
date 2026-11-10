<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjwqvbb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-center" /></template>
<style>
.pjwqvbb_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17V16C7 14.896 7.8941 14 9 14H15C16.1032 14 17 14.897 17 16V17M7 17V18C7 19.106 7.8945 20 9 20H15C16.1037 20 17 19.106 17 18V17M7 17H2M17 17H22M19 7V8C19 9.104 18.1025 10 17 10H7C5.8934 10 5 9.108 5 8V7M19 7V6C19 4.894 18.1011 4 17 4H7C5.892 4 5 4.899 5 6V7M19 7H22M5 7H2");
}

</style>
