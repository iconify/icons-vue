<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzzf3h9_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bill-of-materials" /></template>
<style>
.uzzf3h9_n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 3h2.5q1.036 0 1.768.732T15.75 5.5V7q0 1.036-.732 1.768T13.25 9.5h-.5v2h6.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.261q.876.079 1.518.721q.732.732.732 1.768v1.5q0 1.036-.732 1.768T19.75 21h-1q-1.036 0-1.768-.732T16.25 18.5V17q0-2.372 2.25-2.493V13h-5.75v1.511q.876.079 1.518.721Q15 15.964 15 17v1.5q0 1.036-.732 1.768T12.5 21h-1q-1.036 0-1.768-.732T9 18.5V17q0-2.372 2.25-2.493V13H5.5v1.507q2.25.121 2.25 2.493v1.5q0 1.036-.732 1.768T5.25 21h-1q-1.036 0-1.768-.732T1.75 18.5V17q0-1.036.732-1.768q.642-.642 1.518-.721V12.25q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h6.5v-2h-.5q-2.5 0-2.5-2.5V5.5q0-2.5 2.5-2.5");
}

</style>
