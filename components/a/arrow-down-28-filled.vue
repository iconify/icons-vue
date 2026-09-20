<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="s21adrbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-28-filled" /></template>
<style>
.s21adrbxu {
  fill: currentColor;
  d: path("M23.712 15.703a1 1 0 0 0-1.423-1.406l-7.288 7.376V3.998a1 1 0 1 0-2 0v17.673l-7.287-7.374a1 1 0 0 0-1.422 1.406l8.82 8.927a1.25 1.25 0 0 0 1.779 0z");
}

</style>
