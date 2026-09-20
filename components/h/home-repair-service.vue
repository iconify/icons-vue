<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pny5by3qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-repair-service" /></template>
<style>
.pny5by3qs {
  fill: currentColor;
  d: path("M9 8h6V6H9zM2 20v-5h4v1h2v-1h8v1h2v-1h4v5zm0-6v-4q0-.825.588-1.412T4 8h3V6q0-.825.588-1.412T9 4h6q.825 0 1.413.588T17 6v2h3q.825 0 1.413.588T22 10v4h-4v-2h-2v2H8v-2H6v2z");
}

</style>
