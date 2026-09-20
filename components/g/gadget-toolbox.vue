<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="boaws_bse"/><path class="e9fwu-bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gadget-toolbox" /></template>
<style>
.boaws_bse {
  d: path("M18.73 35.81h-8.365a3.82 3.82 0 0 1-3.83-3.83v-17.2a3.82 3.82 0 0 1 3.83-3.829h24.24a3.82 3.82 0 0 1 3.83 3.83v5.677");
}

.e9fwu-bmh {
  d: path("M13.436 10.952V6.415A1.91 1.91 0 0 1 15.351 4.5h14.268a1.91 1.91 0 0 1 1.915 1.915v4.537M6.535 18.784h31.9m-4.717 10.132l1.752-1.753c1.598-1.598 1.13-3.054-1.062-3.519c-2.347-.498-4.76.574-6.456 2.27a7.92 7.92 0 0 0-1.922 8.022l-3.725 3.726c-1 1-1 2.61 0 3.611l1.481 1.481c1 1 2.61 1 3.611 0l3.725-3.725a7.92 7.92 0 0 0 8.022-1.922a7.88 7.88 0 0 0 2.271-6.455c-.25-2.198-1.901-2.68-3.519-1.063l-1.752 1.753z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
