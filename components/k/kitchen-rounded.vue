<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofqp7fb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:kitchen-rounded" /></template>
<style>
.ofqp7fb-f {
  fill: currentColor;
  d: path("M9.049 7.856q.143-.143.143-.356V5.884q0-.212-.144-.356q-.144-.143-.356-.143q-.213 0-.357.143t-.143.357V7.5q0 .213.144.356T8.693 8t.356-.144m0 8.116q.143-.144.143-.356v-3.347q0-.212-.144-.356t-.356-.144t-.357.144t-.143.356v3.346q0 .213.144.357t.357.143t.356-.143M6.616 21q-.667 0-1.141-.475T5 19.386v-9h14v9q0 .67-.475 1.143q-.474.472-1.14.472zM5 9.385v-4.77q0-.666.475-1.14T6.615 3h10.77q.666 0 1.14.475T19 4.615v4.77z");
}

</style>
