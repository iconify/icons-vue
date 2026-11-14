<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i17enrblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye" /></template>
<style>
.i17enrblp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.25q-6.876 0-10.185 7.445q-.065.146-.065.305t.065.305Q5.124 19.75 12 19.75t10.185-7.445q.065-.146.065-.305t-.065-.305Q18.876 4.25 12 4.25M8.995 8.995Q10.24 7.75 12 7.75t3.005 1.245T16.25 12t-1.245 3.005T12 16.25t-3.005-1.245T7.75 12t1.245-3.005M12 14.75q-2.75 0-2.75-2.75T12 9.25q1.139 0 1.945.805q.805.806.805 1.945t-.805 1.945q-.806.805-1.945.805");
}

</style>
