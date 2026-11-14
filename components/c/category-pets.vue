<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmoribqzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-pets" /></template>
<style>
.fmoribqzc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2.75q-2.75 0-2.75 2.75q0 1.294.609 1.979Q6.294 7.25 5.5 7.25q-2.75 0-2.75 2.75t2.75 2.75T8.25 10q0-1.294-.609-1.979q.565.229 1.359.229q2.75 0 2.75-2.75T9 2.75m3.25 2.75q0-2.75 2.75-2.75t2.75 2.75q0 1.294-.609 1.979q.565-.229 1.359-.229q2.75 0 2.75 2.75t-2.75 2.75T15.75 10q0-1.294.609-1.979q-.565.229-1.359.229q-2.75 0-2.75-2.75M6.75 15q0-2.175 1.538-3.712Q9.825 9.75 12 9.75t3.712 1.538Q17.25 12.825 17.25 15t-1.538 3.712Q14.175 20.25 12 20.25t-3.712-1.538Q6.75 17.175 6.75 15");
}

</style>
