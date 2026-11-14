<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz79lwbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:health-prescription" /></template>
<style>
.dz79lwbao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.972 9.018L5.46 12.531q-1.245 1.244-1.245 3.005T5.46 18.54q1.244 1.245 3.004 1.245t3.005-1.245l3.513-3.512q-.053.048-.114.086t-.129.063t-.138.037t-.142.011t-.142-.017t-.137-.043t-.125-.069q-.06-.04-.11-.091l-4.95-4.95q-.051-.05-.091-.11q-.041-.059-.069-.125q-.028-.067-.043-.137t-.017-.142t.011-.142t.037-.138t.063-.129t.086-.114m.046-.046q.053-.048.114-.086t.129-.063t.138-.037t.142-.011t.142.017t.137.043t.125.069q.06.04.11.091l4.95 4.95q.051.05.091.11q.041.059.069.125q.028.067.043.137t.017.142t-.011.142t-.037.138t-.063.129t-.086.114l3.512-3.513q1.245-1.244 1.245-3.004T18.54 5.46q-1.244-1.245-3.004-1.245T12.531 5.46z");
}

</style>
