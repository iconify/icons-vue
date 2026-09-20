<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usoi-ibci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:heap-snapshot-large-outline-rounded" /></template>
<style>
.usoi-ibci {
  fill: currentColor;
  d: path("M14.5 18.5q.625 0 1.063-.437T16 17t-.437-1.062T14.5 15.5t-1.062.438T13 17t.438 1.063t1.062.437m-5.05-.475q.425 0 .7-.275l5.1-5.1q.275-.275.275-.7t-.275-.7t-.7-.275t-.7.275l-5.1 5.1q-.275.275-.275.7t.275.7t.7.275M9.5 13.5q.625 0 1.063-.438T11 12t-.437-1.062T9.5 10.5t-1.062.438T8 12t.438 1.063T9.5 13.5M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22zm7-15V4H6v16h12V9h-3q-.825 0-1.412-.587T13 7M6 4v5zv16z");
}

</style>
