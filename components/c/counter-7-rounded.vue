<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqafnjb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:counter-7-rounded" /></template>
<style>
.lqafnjb9j {
  fill: currentColor;
  d: path("m13 9l-1.7 6.8q-.125.45.175.825t.775.375q.35 0 .6-.2t.325-.525L14.95 9.25q.05-.125.05-.225V8.8q0-.725-.512-1.262T13.25 7H10q-.425 0-.712.288T9 8t.288.713T10 9zm-1 13q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
