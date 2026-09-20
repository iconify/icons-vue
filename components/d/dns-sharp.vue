<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy9dc3o-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dns-sharp" /></template>
<style>
.xy9dc3o-j {
  fill: currentColor;
  d: path("M7.5 9q.625 0 1.063-.437T9 7.5t-.437-1.062T7.5 6t-1.062.438T6 7.5t.438 1.063T7.5 9m0 10q.625 0 1.063-.437T9 17.5t-.437-1.062T7.5 16t-1.062.438T6 17.5t.438 1.063T7.5 19M3 12V3h18v9zm0 10v-9h18v9z");
}

</style>
