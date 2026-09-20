<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmhzfjbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-flat-outline-rounded" /></template>
<style>
.jmhzfjbxx {
  fill: currentColor;
  d: path("M10.346 13q-.343 0-.575-.232t-.232-.576V9.04q0-.441.299-.74t.739-.3h6.885q1.237 0 2.118.881T20.462 11v1.192q0 .343-.233.576t-.575.232zm.193-4v3zm9.423 6.77H4.039q-.213 0-.357-.145t-.144-.357t.144-.356t.356-.143h15.923q.213 0 .357.144q.143.144.143.357t-.143.356t-.357.143M4.145 12.394q-.606-.606-.606-1.51q0-.903.606-1.509t1.51-.606t1.51.606t.605 1.51t-.606 1.51T5.653 13t-1.509-.606m2.309-.71q.316-.317.316-.8q0-.482-.316-.799q-.316-.316-.8-.316q-.482 0-.798.316q-.317.317-.317.8q0 .482.317.799q.316.316.799.316t.799-.316m4.086.316h8.923v-1q0-.825-.588-1.412T17.462 9h-6.923zm-4.885-1.115");
}

</style>
