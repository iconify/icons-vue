<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcbdzdb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-star" /></template>
<style>
.dcbdzdb9y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.201 4.953l-4.5 3.937Q3.25 10.16 3.25 12.088V16.5q0 1.76 1.245 3.005T7.5 20.75h9q1.76 0 3.005-1.245T20.75 16.5v-4.412q0-1.928-1.451-3.198l-4.5-3.937q-2.799-2.45-5.598 0m3.985 6.256l.166.335q.175.355.565.412l.368.053q.816.118 1.071.901q.254.783-.335 1.357l-.27.261q-.281.274-.214.663l.063.368q.138.811-.526 1.294q-.665.484-1.393.102l-.332-.174q-.349-.184-.698 0l-.331.174q-.729.382-1.394-.102q-.664-.483-.526-1.293l.063-.369q.067-.389-.216-.664l-.266-.259q-.591-.575-.337-1.358q.255-.783 1.069-.901l.372-.053q.388-.057.562-.411l.167-.336q.366-.736 1.186-.736t1.186.735z");
}

</style>
