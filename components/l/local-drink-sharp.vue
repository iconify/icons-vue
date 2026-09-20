<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbn7drffw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-drink-sharp" /></template>
<style>
.lbn7drffw {
  fill: currentColor;
  d: path("M5.2 22L3 2h18l-2.2 20zm.45-14h12.7l.4-4H5.25zm8.375 10.175q.825-.825.825-2.025q0-1.025-.663-2.225T12 11q-1.525 1.725-2.187 2.925T9.15 16.15q0 1.2.825 2.025T12 19t2.025-.825");
}

</style>
