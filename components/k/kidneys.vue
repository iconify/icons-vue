<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ro7cc6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kidneys" /></template>
<style>
.o9ro7cc6o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.766 5.367Q9.847 4.25 8 4.25q-2.759 0-4.567 2.391Q1.75 8.867 1.75 12t1.683 5.359Q5.241 19.75 8 19.75q1.847 0 2.766-1.117q.94-1.141.455-2.839l-.007-.023q-.182-.568-.821-1.543Q9.5 12.866 9.5 12t.893-2.228q.639-.975.821-1.543l.007-.023q.485-1.698-.455-2.839M16 4.25q2.759 0 4.567 2.391Q22.25 8.867 22.25 12t-1.683 5.359Q18.759 19.75 16 19.75q-1.847 0-2.766-1.117q-.94-1.141-.455-2.839l.007-.023q.182-.568.821-1.543q.893-1.362.893-2.228t-.893-2.228q-.639-.975-.821-1.543l-.007-.023q-.485-1.698.455-2.839Q14.153 4.25 16 4.25");
}

</style>
