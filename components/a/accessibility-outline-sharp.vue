<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt1m5_bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:accessibility-outline-sharp" /></template>
<style>
.xt1m5_bem {
  fill: currentColor;
  d: path("M10.588 5.413Q10 4.825 10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6t-1.412-.587M9 22V9H3V7h18v2h-6v13h-2v-6h-2v6z");
}

</style>
