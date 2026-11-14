<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_j-t374g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dhcp" /></template>
<style>
.f_j-t374g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 6.5q0-1.76 1.245-3.005T12 2.25t3.005 1.245T16.25 6.5t-1.245 3.005q-.971.971-2.255 1.185v2.06h6.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.761q.876.079 1.518.721q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-1q-2.5 0-2.5-2.5v-1q0-2.372 2.25-2.493V14.25h-5.75v1.011q.876.079 1.518.721q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-1q-2.5 0-2.5-2.5v-1q0-2.372 2.25-2.493V14.25H5.5v1.007q2.25.121 2.25 2.493v1q0 2.5-2.5 2.5h-1q-2.5 0-2.5-2.5v-1q0-1.036.732-1.768q.642-.642 1.518-.721V13.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h6.5v-2.06q-1.284-.214-2.255-1.185Q7.75 8.26 7.75 6.5");
}

</style>
