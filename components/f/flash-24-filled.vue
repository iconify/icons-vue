<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8au5abbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-24-filled" /></template>
<style>
.a8au5abbe {
  fill: currentColor;
  d: path("M7.425 2.83A1.25 1.25 0 0 1 8.603 2h6.453a1.25 1.25 0 0 1 1.186 1.645L14.79 8h3.96c1.103 0 1.665 1.327.897 2.12L8.586 21.536c-1.054 1.088-2.872.106-2.541-1.372l1.27-5.668l-1.57-.006a1.75 1.75 0 0 1-1.641-2.337z");
}

</style>
