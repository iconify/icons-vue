<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te0yi8b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:clarify-outline" /></template>
<style>
.te0yi8b8i {
  fill: currentColor;
  d: path("M6 17h7v-2H6zm10 0h2V7h-2zM6 13h7v-2H6zm0-4h7V7H6zM4 21q-.825 0-1.412-.587T2 19V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v14q0 .825-.587 1.413T20 21zm0-2h16V5H4zm0 0V5z");
}

</style>
