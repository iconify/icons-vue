<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eftpq-i0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gaze-target" /></template>
<style>
.eftpq-i0z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.817 11.69Q5.54 3.5 12 3.5t10.183 8.19q.067.148.067.31t-.067.31Q18.46 20.5 12 20.5T1.817 12.31q-.067-.148-.067-.31t.067-.31m6.471-3.402Q6.75 9.825 6.75 12t1.538 3.712Q9.825 17.25 12 17.25t3.712-1.538Q17.25 14.175 17.25 12t-1.538-3.712Q14.175 6.75 12 6.75T8.288 8.288");
}

</style>
