<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngm2qlbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-insert-sharp" /></template>
<style>
.ngm2qlbef {
  fill: currentColor;
  d: path("M17.6 18L8 8.4V17H6V5h12v2H9.4l9.6 9.6z");
}

</style>
