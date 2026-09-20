<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nexskpdoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-color-fill-outline" /></template>
<style>
.nexskpdoa {
  fill: currentColor;
  d: path("m6.598 2.573l.694-.727l8.133 8.133q.479.479.479 1.156t-.479 1.156l-3.904 3.942q-.46.46-1.136.46q-.677 0-1.137-.46L5.344 12.29q-.479-.48-.479-1.156q0-.677.48-1.156L9.69 5.665zm3.806 3.806l-4.39 4.352q-.097.096-.125.202q-.03.106-.03.22h9.05q0-.114-.028-.22t-.125-.202zm7.107 10.88q-.434-.434-.434-1.067q0-.448.236-.884t.495-.827q.186-.262.378-.51q.193-.248.391-.51q.198.262.39.51q.193.248.38.51q.259.39.494.827q.236.436.236.884q0 .633-.434 1.067q-.433.433-1.066.433t-1.066-.433M2 24v-2h20v2z");
}

</style>
