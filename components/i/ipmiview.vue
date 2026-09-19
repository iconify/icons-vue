<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tplugybck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ipmiview" /></template>
<style>
.tplugybck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 33.317l2.727-3.988l2.878 9.293l2.641-26.484l4.815 22.882l3.03-3.259l2.367 5.502l2.914-9.276l2.541 4.504l2.683-23.113l1.16 14.374l2.818-5.17l2.488 2.704l2.614 7.769H43.5");
}

</style>
