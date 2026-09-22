<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oopy7r-0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-plus-rounded" /></template>
<style>
.oopy7r-0m {
  fill: currentColor;
  d: path("M9.27 19q-.328 0-.549-.221T8.5 18.23v-5.577L3.104 5.83q-.065-.066-.085-.152Q3 5.594 3 5.515q0-.198.143-.356Q3.286 5 3.519 5h11.962q.234 0 .376.161t.143.354q0 .077-.02.164q-.019.086-.084.152L10.5 12.654v5.577q0 .327-.221.548T9.73 19zm7.768-2.961h-2.48q-.213 0-.357-.145t-.143-.356t.143-.356t.357-.144h2.48v-2.48q0-.213.144-.357q.144-.143.357-.143t.356.143t.144.357v2.48H20.5q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143h-2.461V18.5q0 .213-.145.356t-.356.144t-.356-.144t-.144-.356z");
}

</style>
