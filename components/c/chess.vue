<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywg05pb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess" /></template>
<style>
.ywg05pb8c {
  fill: currentColor;
  d: path("M3 22v-4q0-.825.588-1.412T5 16h1.3l.55-4H4v-2h16v2h-2.85l.55 4H19q.825 0 1.413.588T21 18v4zM6.45 8.5L5 2q.825.625 1.7 1.175t1.925.55q1 0 1.838-.513T12 2q.7.7 1.538 1.213t1.837.512q1.05 0 1.925-.55T19 2l-1.425 6.5z");
}

</style>
