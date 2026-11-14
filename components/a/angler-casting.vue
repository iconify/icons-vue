<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z62dc-rfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:angler-casting" /></template>
<style>
.z62dc-rfc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.838 16.962q-1.028 1.741-2.009 3.703q-.033.066-.052.137q-.02.071-.025.145t.004.147t.032.143t.06.134q.037.065.085.12q.049.056.107.101q.059.046.125.079q.133.067.282.077q.149.011.29-.036q.142-.048.254-.145q.113-.098.18-.232q1.024-2.047 2.095-3.841q.114.006.234.006q2.25 0 2.25-2.25q0-.706-.221-1.19q4.985-6.821 10.915-8.628q1.059 5.102-1.329 8.339Q16 14.011 16 17q0 3.25 2.5 3.25q1.115 0 1.852-1.052Q21 18.272 21 17t-.648-2.198q-.298-.426-.659-.679q2.508-3.91 1.035-9.805q-.018-.072-.05-.138q-.031-.067-.075-.126q-.044-.06-.099-.109q-.055-.05-.118-.088t-.133-.063t-.143-.036t-.146-.007q-.074.003-.146.021Q12.97 5.484 7.37 13.106Q6.988 13 6.5 13q-2.25 0-2.25 2.25q0 1.15.588 1.712");
}

</style>
