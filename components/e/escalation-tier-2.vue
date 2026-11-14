<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-2utebcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:escalation-tier-2" /></template>
<style>
.i-2utebcc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.487 2.453l-4 3.75q-.054.05-.097.11t-.073.128t-.047.139t-.02.146t.01.147q.012.072.038.142t.065.131q.039.063.09.117t.11.097t.128.073q.067.031.139.047q.072.017.146.02t.147-.01t.142-.038t.131-.065t.117-.09L12 4.028l3.487 3.269q.054.051.117.09q.062.039.131.065q.07.026.142.038q.073.012.147.01q.074-.003.146-.02q.072-.016.139-.047q.068-.03.128-.073t.11-.097q.102-.109.155-.248q.052-.14.048-.289q-.005-.149-.067-.285q-.061-.136-.17-.238l-4-3.75q-.052-.049-.112-.086q-.059-.038-.125-.064t-.136-.04T12 2.25t-.14.013q-.07.014-.136.04t-.125.064t-.112.086m6.763 9.172q0-2.875-2.875-2.875h-6.75q-2.875 0-2.875 2.875T8.625 14.5h6.75q2.875 0 2.875-2.875M3.129 16.629q.878-.879 2.121-.879h13.5q3 0 3 3t-3 3H5.25q-1.243 0-2.121-.879q-.879-.878-.879-2.121t.879-2.121");
}

</style>
