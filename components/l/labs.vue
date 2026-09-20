<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8s2w7bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:labs" /></template>
<style>
.f8s2w7bkh {
  fill: currentColor;
  d: path("M12 22q-2.075 0-3.537-1.463T7 17V8q-.825 0-1.412-.587T5 6V4q0-.825.588-1.412T7 2h10q.825 0 1.413.588T19 4v2q0 .825-.587 1.413T17 8v9q0 2.075-1.463 3.538T12 22m2.125-2.875Q15 18.25 15 17h-3v-2h3v-2h-3v-2h3V8H9v9q0 1.25.875 2.125T12 20t2.125-.875");
}

</style>
