<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyanz5b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ifr-conditions" /></template>
<style>
.qyanz5b8o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.652 14.32q1.056 3.923 4.945 2.93h5.949q.226-1.8 1.565-3.139Q15.722 12.5 18 12.5q.792 0 1.504.195q.084-1.904-1.186-3.343q-1.164-1.318-2.854-1.558q-2.072-3.506-6.226-2.898q-4.129.604-5.123 4.512q-3.471 1.167-2.463 4.912m13.343.675Q13.75 16.24 13.75 18t1.245 3.005T18 22.25t3.005-1.245T22.25 18q0-1.636-1.075-2.826q-.055-.115-.145-.204q-.089-.09-.204-.145Q19.636 13.75 18 13.75q-1.76 0-3.005 1.245m2.475 2.475q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l1.876-1.876q.344.602.344 1.346q0 1.139-.805 1.945q-.806.805-1.945.805q-2.75 0-2.75-2.75T18 15.25q.744 0 1.346.344z");
}

</style>
