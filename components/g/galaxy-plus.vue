<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vb3uzzbpq"/><path class="m2au9ac6f"/><path class="dwdcjxbxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:galaxy-plus" /></template>
<style>
.dwdcjxbxu {
  d: path("M12.5 10a3 5.5 0 0 0-3-5.5a7 11 0 0 0-7 11M18 15v6m-3-3h6");
}

.m2au9ac6f {
  d: path("M8.5 10q0 .135.004.27q.003.135.01.269l.018.268q.011.134.026.266t.032.263q.018.131.039.261q.022.129.046.256q.025.127.053.252q.029.124.06.247q.032.122.066.241q.035.119.073.235t.079.228t.084.22q.044.109.091.213q.047.105.096.205q.05.1.102.195q.052.096.106.186q.055.091.112.177t.116.166t.12.155t.125.145t.128.133t.131.121t.135.109t.137.097t.14.085t.142.072t.144.059q.072.027.145.046q.073.02.146.034q.073.013.147.019q.073.007.147.007q.352 0 .702-.055m.867-.225q.573-.207 1.117-.562q.543-.355 1.041-.847m1.247-1.572q.241-.381.456-.798t.405-.864q.189-.448.349-.922t.29-.971t.228-1.011t.165-1.04t.1-1.062q.033-.534.033-1.071");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vb3uzzbpq {
  d: path("M8.5 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
