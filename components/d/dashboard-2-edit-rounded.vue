<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etzowg06x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-edit-rounded" /></template>
<style>
.etzowg06x {
  fill: currentColor;
  d: path("M14.23 20.192V19.12q0-.153.057-.296q.055-.144.186-.275l5.09-5.065q.149-.13.306-.19t.315-.062q.172 0 .338.064q.166.065.301.194l.925.944q.123.148.188.308q.064.159.064.319t-.052.322t-.2.31l-5.065 5.066q-.131.13-.275.186q-.143.056-.297.056h-1.073q-.343 0-.575-.232t-.232-.576m5.96-4.177l.925-.956l-.925-.944l-.95.95zM11.192 10V5.815q0-.355.233-.585T12 5h8.192q.344 0 .576.232t.232.576v4.185q0 .355-.232.585q-.233.23-.576.23H12q-.343 0-.575-.232T11.192 10M3 18.192v-4.184q0-.356.232-.586t.576-.23H11q.343 0 .576.232t.232.576v4.185q0 .356-.232.585T11 19H3.808q-.343 0-.576-.232T3 18.192M3 10V5.815q0-.355.232-.585T3.808 5h4.185q.355 0 .585.232t.23.576v4.185q0 .355-.232.585q-.233.23-.576.23H3.815q-.355 0-.585-.232T3 10");
}

</style>
