<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8kvbd1sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coffee-sack" /></template>
<style>
.l8kvbd1sp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 14q0-4.903 4.327-8.249L6.311 2.795q-.059-.137-.061-.286t.054-.288q.055-.138.159-.245t.242-.165q.113-.049.235-.059q.123-.009.242.02q4.818 1.205 9.636 0q.072-.018.146-.021q.073-.004.146.007t.143.036t.133.063t.118.088q.055.049.099.109q.044.059.075.126q.032.066.05.138q.029.119.02.242q-.01.122-.059.235l-1.266 2.956Q20.75 9.097 20.75 14v4.5q0 3.75-3.75 3.75H7q-3.75 0-3.75-3.75zm1.5 1.75v2.75q0 2.25 2.25 2.25h10q2.25 0 2.25-2.25v-2.75zm14.5-1.5H4.75V14q0-4.298 3.994-7.25h6.512Q19.25 9.702 19.25 14zm-4.245-9l.734-1.712q-3.739.675-7.478 0l.734 1.712z");
}

</style>
