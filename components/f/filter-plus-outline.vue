<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yywzc_r7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-plus-outline" /></template>
<style>
.yywzc_r7d {
  fill: currentColor;
  d: path("M9.27 19q-.328 0-.549-.221T8.5 18.23v-5.577L3.104 5.83q-.065-.066-.085-.152Q3 5.594 3 5.515q0-.198.143-.356Q3.286 5 3.519 5h11.962q.234 0 .376.161t.143.354q0 .077-.02.164q-.019.086-.084.152L10.5 12.654v5.577q0 .327-.221.548T9.73 19zm.23-6.7L14.45 6h-9.9zm7.539 6.7v-2.962h-2.981v-1h2.98v-2.98h1v2.98H21v1h-2.962V19z");
}

</style>
