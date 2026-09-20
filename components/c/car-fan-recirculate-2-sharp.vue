<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciy-inntp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:car-fan-recirculate-2-sharp" /></template>
<style>
.ciy-inntp {
  fill: currentColor;
  d: path("m9.25 15l1.05-1.05l-.675-.7h2q1.2 0 2.038-.837t.837-2.038t-.837-2.037t-2.038-.838H7.25V9h4.375q.575 0 .975.4t.4.975t-.4.975t-.975.4h-2l.675-.675L9.25 10l-2.5 2.5zM6.5 20q-1.025 0-1.875-.537T3.35 18H0v-8h3l2-5.5h10l3 5l6 .5v8h-3.35q-.425.925-1.275 1.463T17.5 20t-1.875-.537T14.35 18h-4.7q-.425.925-1.275 1.463T6.5 20");
}

</style>
