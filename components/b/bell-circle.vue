<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="o8lukym1v"/><path clip-rule="evenodd" class="axsn4ubiv"/><path class="bc1985bbo"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bell-circle" /></template>
<style>
.axsn4ubiv {
  fill-rule: evenodd;
  d: path("M21 17.5a3.46 3.46 0 0 0-1.5-2.851V12a6 6 0 0 0-6-6h-1a6 6 0 0 0-6 6v2.649A3.46 3.46 0 0 0 5 17.5A2.5 2.5 0 0 0 7.5 20h11a2.5 2.5 0 0 0 2.5-2.5m-3.5-1.618l.59.265l.053.024c.522.236.857.756.857 1.329a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5c0-.573.335-1.093.857-1.33l.053-.023l.59-.265V12a4 4 0 0 1 4-4h1a4 4 0 0 1 4 4z");
}

.bc1985bbo {
  d: path("M12 4.5a1 1 0 0 1 2 0V7a1 1 0 1 1-2 0z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.o8lukym1v {
  d: path("M10.5 20a1 1 0 1 1 2 0a.5.5 0 0 0 1 0a1 1 0 1 1 2 0a2.5 2.5 0 0 1-5 0");
}

</style>
