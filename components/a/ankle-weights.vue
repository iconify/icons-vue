<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjh33-bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ankle-weights" /></template>
<style>
.qjh33-bdv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.023 4.321Q1.751 5.527 1.75 7.499V11.5q0 1.973 3.273 3.179q.235.086.477.166V13.5q0-.122.005-.243Q3.25 12.419 3.25 11.5V9.819q.716.47 1.773.86q.507.187 1.05.341q.388-.759 1.038-1.409Q8.722 8 11 8h2q2.278 0 3.889 1.611q.65.65 1.038 1.409q.543-.154 1.05-.341q1.057-.39 1.773-.86V11.5q0 .919-2.255 1.757q.005.121.005.243v1.345q.242-.08.477-.166q3.273-1.206 3.273-3.179v-4q0-1.973-3.273-3.179Q16.069 3.25 12 3.25T5.023 4.321m2.972 6.174Q9.24 9.25 11 9.25h2q1.76 0 3.005 1.245T17.25 13.5v2q0 1.76-1.245 3.005T13 19.75h-2q-1.76 0-3.005-1.245T6.75 15.5v-2q0-1.76 1.245-3.005M11 10.75q-2.75 0-2.75 2.75v2q0 2.75 2.75 2.75h2q2.75 0 2.75-2.75v-2q0-2.75-2.75-2.75zm1 5q1.308 0 2.497-.111q.003-.068.003-.139v-1.368q-1.181.118-2.5.118t-2.5-.118V15.5q0 .071.003.139q1.189.111 2.497.111");
}

</style>
