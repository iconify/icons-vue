<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4sey8r_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ivy" /></template>
<style>
.k4sey8r_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.32 12.25l1.2.28q.58.14 1.01-.28l.57-.57q.43-.42.7.11l.75 1.48q.27.54-.22.89l-.34.24q-.49.35-.65.93l-.11.41q-.17.57-.76.5l-1.65-.2q-.59-.07-.34-.61l.34-.74q.25-.54-.08-1.05l-.67-1.02q-.33-.5.25-.37m13.61-3.88l-.67 1.02q-.33.51-.08 1.05l.34.74q.25.54-.34.61l-1.65.2q-.59.07-.76-.5l-.11-.41q-.16-.58-.65-.93l-.34-.24q-.49-.35-.22-.89l.75-1.48q.27-.53.7-.11l.57.57q.43.42 1.01.28l1.2-.28q.58-.13.25.37M5.32 3.75l1.2.28q.58.14 1.01-.28l.57-.57q.43-.42.7.11l.75 1.48q.27.54-.22.89l-.34.24q-.49.35-.65.93l-.11.41q-.17.57-.76.5l-1.65-.2q-.59-.07-.34-.61l.34-.74q.25-.54-.08-1.05l-.67-1.02q-.33-.5.25-.37M12 21.25V3.5M12 17l-3.5-2.25m3.5-2l3.5-2.25m-3.5-2L8.5 6.25");
}

</style>
