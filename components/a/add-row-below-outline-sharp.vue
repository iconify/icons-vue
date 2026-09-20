<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sylkw0bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-row-below-outline-sharp" /></template>
<style>
.sylkw0bey {
  fill: currentColor;
  d: path("M5 10.558h14V4H5zM4 19V3h16v16h-3.116v-1H19v-6.442H5V18h2.116v1zm8-8.442v1zM11.5 21v-2h-2v-1h2v-2h1v2h2v1h-2v2z");
}

</style>
