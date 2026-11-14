<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqy6h2b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bokeh" /></template>
<style>
.dqy6h2b1i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.215 10.242q.035.372.035.758q0 .519-.063 1.012q1.122.373 2.025 1.276Q20.75 14.825 20.75 17t-1.538 3.712Q17.675 22.25 15.5 22.25t-3.712-1.538q-1.079-1.079-1.401-2.471q-.192.009-.387.009q-3.003 0-5.127-2.123T2.75 11t2.123-5.127Q6.997 3.75 10 3.75q1.913 0 3.47.862q.303-.895 1.025-1.617Q15.74 1.75 17.5 1.75t3.005 1.245T21.75 6t-1.245 3.005T17.5 10.25q-.144 0-.285-.008");
}

</style>
