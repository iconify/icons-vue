<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p77izkbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hand-gesture-sharp" /></template>
<style>
.p77izkbuv {
  fill: currentColor;
  d: path("M22 5.025q0-1.275-.875-2.15T18.975 2V.5q1.875 0 3.2 1.325t1.325 3.2zM6 23q-2.075 0-3.537-1.463T1 18h1.5q0 1.45 1.025 2.475T6 21.5zm2.475 0L1.2 12.375l1.725-1.65L7 13.575V3h2v9h2V1h2v11h2V2h2v10h2V4h2v19z");
}

</style>
