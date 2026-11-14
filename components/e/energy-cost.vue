<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx2_7ebaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:energy-cost" /></template>
<style>
.fx2_7ebaw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-3.831 2.709-6.541Q7.169 2.75 11 2.75h2q3.831.001 6.539 2.71T22.247 12t-2.708 6.54T13 21.25h-2q-3.831 0-6.541-2.709Q1.75 15.831 1.75 12m16.68 5.527l.048-.048q2.269-2.27 2.269-5.479t-2.269-5.479l-.048-.048Q20.25 8.859 20.25 12t-1.82 5.527m-8.28-9.603l-.002.002l-2.391 2.988q-.626.781-.192 1.684t1.436.902q.318 0 .519.248t.135.56l-.139.663q-.213 1.025.733 1.472q.945.447 1.601-.367l2.393-2.99q.626-.781.192-1.684t-1.436-.902q-.318 0-.519-.248t-.135-.56l.139-.663q.213-1.025-.733-1.472q-.945-.447-1.601.367");
}

</style>
