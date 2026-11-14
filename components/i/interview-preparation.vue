<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm_2qabrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:interview-preparation" /></template>
<style>
.mm_2qabrd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 8.75q-.001-3.091 2.029-5.284Q9.083 1.248 12 1.248t4.971 2.218Q19.001 5.66 19 8.75q.001 3.09-2.029 5.284q-1.346 1.453-3.062 1.955q.091.335.091.761v3.5q0 2-2 2t-2-2v-3.5q0-.426.091-.761q-1.716-.502-3.062-1.955Q4.999 11.841 5 8.75M9.75 6Q8 6 8 7.75v2q0 1.479 1.25 1.708V12q0 .132.045.255q.045.124.129.225q.047.057.105.103q.057.047.122.081q.066.034.137.055t.144.028t.147-.001t.144-.03t.136-.057q.064-.036.121-.083l1.292-1.076h2.478Q16 11.5 16 9.75v-2Q16 6 14.25 6z");
}

</style>
