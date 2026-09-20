<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y58vplbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-edit-outline-rounded" /></template>
<style>
.y58vplbsw {
  fill: currentColor;
  d: path("M14.23 20.192V19.12q0-.153.057-.296q.055-.144.186-.275l5.09-5.065q.149-.148.306-.2q.158-.052.315-.052q.172 0 .338.064q.166.065.301.194l.925.944q.123.148.188.308q.064.159.064.319t-.061.322t-.191.31l-5.065 5.066q-.131.13-.275.186q-.143.056-.297.056h-1.073q-.343 0-.575-.232t-.232-.576m6.884-5.133l-.925-.944zm-6 5.056h.95l3.468-3.473l-.47-.475l-.455-.488l-3.493 3.486zm3.948-3.948l-.455-.488l.925.963zM11.193 10V5.815q0-.355.232-.585T12 5h8.192q.344 0 .576.232t.232.576v4.185q0 .355-.232.585q-.233.23-.576.23H12q-.343 0-.575-.232T11.192 10M3 18.192v-4.184q0-.356.232-.586t.576-.23H11q.343 0 .576.232t.232.576v4.185q0 .356-.232.585T11 19H3.808q-.343 0-.576-.232T3 18.192M3 10V5.815q0-.355.232-.585T3.808 5h4.185q.355 0 .585.232t.23.576v4.185q0 .355-.232.585q-.233.23-.576.23H3.815q-.355 0-.585-.232T3 10m9.192-.192H20V6h-7.808zM4 18h6.808v-3.808H4zm0-8.192h3.808V6H4zm3.808 0");
}

</style>
