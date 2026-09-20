<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ji75-1b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cut-28-regular" /></template>
<style>
.ji75-1b2k {
  fill: currentColor;
  d: path("M7.332 2.127a.75.75 0 0 1 .995.143l.046.062l9.495 14.145a5 5 0 1 1-1.244.837l-2.625-3.909l-2.623 3.91a5 5 0 1 1-1.244-.837l2.964-4.419l-5.97-8.891l-.038-.066a.75.75 0 0 1 .244-.975M8 17.5a3.5 3.5 0 1 0 2.122.717l-.172-.124A3.5 3.5 0 0 0 8 17.5m12 0c-.723 0-1.393.218-1.95.593l-.172.124A3.5 3.5 0 1 0 20 17.5m-.327-15.23a.751.751 0 0 1 1.24.832l-.04.066l-5.368 7.995l-.903-1.346l5.025-7.485z");
}

</style>
