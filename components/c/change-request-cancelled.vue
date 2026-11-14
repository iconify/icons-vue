<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm8lkvb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:change-request-cancelled" /></template>
<style>
.qm8lkvb6m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h7.504q-.201-.169-.393-.361Q12.5 20.278 12.5 18t1.611-3.889T18 12.5q1.221 0 2.25.463V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zm.964 13.025Q13.75 16.24 13.75 18t1.245 3.005T18 22.25t3.005-1.245T22.25 18t-1.245-3.005T18 13.75t-3.005 1.245M18 15.25q.744 0 1.346.344l-3.837 3.836q-.259-.585-.259-1.43q0-2.75 2.75-2.75m0 5.5q-.845 0-1.43-.259l3.836-3.837q.344.602.344 1.346q0 1.139-.805 1.945q-.806.805-1.945.805");
}

</style>
