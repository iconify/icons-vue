<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snm8d9bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:body-piercing" /></template>
<style>
.snm8d9bpe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.204 9.953Q18.716 5.94 14.74 4.682Q14.586 2.25 12 2.25T9.26 4.682Q5.284 5.94 3.796 9.953q-1.59 4.287 1.021 8.04T12 21.746t7.183-3.753t1.021-8.04m-15.002.522q1.176-3.169 4.222-4.264Q9.942 7.75 12 7.75t2.576-1.539q3.046 1.095 4.222 4.264q1.317 3.552-.847 6.661q-2.163 3.11-5.951 3.11t-5.951-3.11q-2.164-3.109-.847-6.661");
}

</style>
