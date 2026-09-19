<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncj_yjbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:edit-location" /></template>
<style>
.ncj_yjbzh {
  fill: currentColor;
  d: path("M12 2C8.14 2 5 5.14 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.86-3.14-7-7-7m-1.56 10H9v-1.44l3.35-3.34l1.43 1.43zm4.45-4.45l-.7.7l-1.44-1.44l.7-.7a.38.38 0 0 1 .54 0l.9.9c.15.15.15.39 0 .54");
}

</style>
