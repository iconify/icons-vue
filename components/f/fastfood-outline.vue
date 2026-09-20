<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7fuu-xpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fastfood-outline" /></template>
<style>
.p7fuu-xpk {
  fill: currentColor;
  d: path("M13.325 13q-.8-1.125-2.112-1.562T8.5 11t-2.713.438T3.675 13zM1 15q0-2.725 2.275-4.362T8.5 9t5.225 1.638T16 15zm0 4v-2h15v2zm17 4v-2h1.4l1.4-14h-9.55L11 5h5V1h2v4h5l-1.65 16.55q-.075.625-.55 1.038T19.7 23zm0-2h1.4zM2 23q-.425 0-.712-.288T1 22v-1h15v1q0 .425-.288.713T15 23zm6.5-10");
}

</style>
