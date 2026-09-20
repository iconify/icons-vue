<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ease7z1rj"/><path class="pxn85tbho"/></g><g class="to-5kdesz"><path class="wfpy3gbmy"/><path class="abq6bsu5h"/><path class="is-ytvijl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-kash-18" /></template>
<style>
.abq6bsu5h {
  stroke-linecap: round;
  d: path("M39.9 16.105v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953m-12.961-3l.016 6");
}

.ease7z1rj {
  d: path("m16.663 27.465l2.799-1.54m0 0v11.2m8.558-5.6H26.2c-1.54 0-2.8 1.26-2.8 2.8s1.26 2.8 2.8 2.8h1.82c1.54 0 2.8-1.26 2.8-2.8s-1.26-2.8-2.8-2.8");
}

.is-ytvijl {
  d: path("M39.9 16.105a3.985 3.985 0 1 0 0-7.97c-.086 0-.167.02-.253.025c-.653-2.124-2.608-3.677-4.946-3.677S30.41 6.036 29.755 8.16c-.085-.005-.166-.025-.252-.025a3.985 3.985 0 1 0 0 7.97z");
}

.pxn85tbho {
  d: path("M28.02 31.525c1.54 0 2.8-1.26 2.8-2.8s-1.26-2.8-2.8-2.8H26.2c-1.54 0-2.8 1.26-2.8 2.8s1.26 2.8 2.8 2.8");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.wfpy3gbmy {
  stroke-linecap: round;
  d: path("M39.9 19.661h-33m33-3.556v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
