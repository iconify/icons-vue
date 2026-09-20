<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml9s0_bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:leaf-one-24-filled" /></template>
<style>
.ml9s0_bwj {
  fill: currentColor;
  d: path("M11.037 3.048a1.75 1.75 0 0 1 2.2.224l3.712 3.712A6.999 6.999 0 0 1 12.75 18.89v2.359a.75.75 0 1 1-1.5 0V18.89A6.999 6.999 0 0 1 7.051 6.984l3.712-3.712a2 2 0 0 1 .274-.224M12 11a.75.75 0 0 0-.75.75v5.63a5.5 5.5 0 0 0 1.5 0v-5.63A.75.75 0 0 0 12 11");
}

</style>
