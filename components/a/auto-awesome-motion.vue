<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbtxc97wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-awesome-motion" /></template>
<style>
.tbtxc97wm {
  fill: currentColor;
  d: path("M12 22q-.825 0-1.412-.587T10 20v-8q0-.825.588-1.412T12 10h8q.825 0 1.413.588T22 12v8q0 .825-.587 1.413T20 22zm-6-4V8q0-.825.588-1.412T8 6h10v2H8v10zm-4-4V4q0-.825.588-1.412T4 2h10v2H4v10z");
}

</style>
