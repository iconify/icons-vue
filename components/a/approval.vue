<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mngie1vxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:approval" /></template>
<style>
.mngie1vxk {
  fill: currentColor;
  d: path("M4 22v-6q0-.825.588-1.412T6 14h12q.825 0 1.413.588T20 16v6zm2-4h12v-2H6zm6-4L7 7q0-2.075 1.463-3.537T12 2t3.538 1.463T17 7z");
}

</style>
