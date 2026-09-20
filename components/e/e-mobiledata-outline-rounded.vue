<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf6vydh7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:e-mobiledata-outline-rounded" /></template>
<style>
.tf6vydh7f {
  fill: currentColor;
  d: path("M9 17q-.425 0-.712-.288T8 16V8q0-.425.288-.712T9 7h6q.425 0 .713.288T16 8t-.288.713T15 9h-5v2h5q.425 0 .713.288T16 12t-.288.713T15 13h-5v2h5q.425 0 .713.288T16 16t-.288.713T15 17z");
}

</style>
