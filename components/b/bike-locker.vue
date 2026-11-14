<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etjm882xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-locker" /></template>
<style>
.etjm882xh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 3.25h-11q-1.76 0-3.005 1.245T2.25 7.5v9q0 1.76 1.245 3.005T6.5 20.75h11q1.76 0 3.005-1.245T21.75 16.5v-9q0-1.76-1.245-3.005T17.5 3.25m-7.264 8.749Q11 12.841 11 14q0 1.243-.879 2.121Q9.243 17 8 17q-3 0-3-3t3-3q.529 0 .992.159l1.384-2.075q.051-.077.12-.139q.068-.063.15-.106q.082-.044.172-.066T11 8.75h3.5q.059 0 .117.009t.113.027q.056.018.109.045q.052.026.1.061q.047.034.089.075t.076.089q.035.047.062.099t.046.108l.58 1.741Q15.894 11 16 11q1.243 0 2.121.879Q19 12.757 19 14t-.879 2.121Q17.243 17 16 17q-3 0-3-3q0-1.992 1.322-2.661l-.363-1.089h-2.558z");
}

</style>
