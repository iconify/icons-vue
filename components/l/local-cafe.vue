<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei8pmybdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-cafe" /></template>
<style>
.ei8pmybdy {
  fill: currentColor;
  d: path("M4 21v-2h16v2zm4-4q-1.65 0-2.825-1.175T4 13V3h16q.825 0 1.413.588T22 5v3q0 .825-.587 1.413T20 10h-2v3q0 1.65-1.175 2.825T14 17zm10-9h2V5h-2z");
}

</style>
