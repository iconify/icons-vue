<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g28q58p8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:artwork-crate" /></template>
<style>
.g28q58p8k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 .732-.178 1.39q-.02-.024-.042-.045l-5-5q-.105-.106-.243-.163T16 12.75t-.287.057t-.243.163l-1.97 1.969l-4.47-4.469q-.105-.106-.243-.163T8.5 10.25t-.287.057t-.243.163l-5.5 5.5q-.106.105-.163.243q-.057.137-.057.286V7.375q0-2.123 1.501-3.624T7.375 2.25M12.75 8.5q0 2.75 2.75 2.75t2.75-2.75t-2.75-2.75t-2.75 2.75m7.72 10.53q.113.113.262.171q.15.057.309.048q-.322.53-.792 1q-1.501 1.501-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-.124q0 .149.057.286q.057.138.163.243q.105.106.243.163T3 17.25t.287-.057t.243-.163l4.97-4.969l4.47 4.469q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094L16 14.561z");
}

</style>
