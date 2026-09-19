<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ymg-yz19h"/><path class="fu2n1db4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:car4way" /></template>
<style>
.fu2n1db4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.746 25.08l3.304-.032v-1.565h9.977v1.537h3.375v-6.386l-1.385-1.384l1.746-.468v-.818l-.534-.533h-2.453l-.76-2.84h-9.871l-.747 2.787h-2.623l-.413.412v.67l1.66.959l-1.385 1.386z");
}

.ymg-yz19h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.042 43.5c-8.229-7.661-14.51-14.633-15.138-23.77c.283-20.614 30.543-19.997 30.19 0c-.832 9.913-8.136 16.75-15.052 23.77");
}

</style>
