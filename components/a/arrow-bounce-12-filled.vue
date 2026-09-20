<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lpg-mmv5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bounce-12-filled" /></template>
<style>
.lpg-mmv5o {
  fill: currentColor;
  d: path("M1 3.75A.75.75 0 0 1 1.75 3h3.5a.75.75 0 0 1 0 1.5H3.56L6.5 7.44l3.22-3.22a.75.75 0 1 1 1.06 1.06L7.03 9.03a.75.75 0 0 1-1.06 0L2.5 5.56v1.69a.75.75 0 0 1-1.5 0z");
}

</style>
