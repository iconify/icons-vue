<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_-9j6_4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:accident-cleared" /></template>
<style>
.l_-9j6_4j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.972 15.728l-5.026-8.993Q13.979 5.007 12 5.007T9.054 6.735l-5.026 8.993q-.943 1.687.035 3.355t2.911 1.667h10.052q1.933 0 2.911-1.667t.035-3.355m-9.009-.075l2.973-3.397q.048-.055.107-.101q.058-.045.125-.077q.066-.033.137-.052t.145-.024t.147.004q.073.01.143.034q.07.023.134.06t.12.086t.101.107t.077.125q.033.066.052.137t.024.145t-.004.147q-.01.073-.034.143q-.023.07-.06.134t-.086.12l-3.5 4q-.016.019-.034.036q-.052.053-.113.094t-.13.069t-.141.043T11 17.5t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-2-2q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T9 14t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
