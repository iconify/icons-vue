<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxe745ato"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-alluvial" /></template>
<style>
.oxe745ato {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 1.75q1.428 0 1.836 1.019q3.48.228 6.902 3.162q2.999 2.57 5.943 2.797q.42-.978 1.819-.978q2 0 2 2v4.5q0 .828-.586 1.414t-1.414.586t-1.414-.586q-.2-.199-.331-.427q-3.508-.179-6.968-2.897q-2.915-2.291-5.787-2.555v.465q0 2-2 2t-2-2v-6.5q0-.828.586-1.414T3.75 1.75m0 11.5q2 0 2 2v1.512q3.242.108 6.48 1.149q3.017.97 6.029 1.076q.127-1.737 1.991-1.737q2 0 2 2v1q0 2-2 2q-1.877 0-1.992-1.762q-3.246-.107-6.488-1.149q-3.012-.968-6.02-1.076v1.987q0 2-2 2t-2-2v-5q0-.828.586-1.414t1.414-.586");
}

</style>
