<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijtl6r9ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cursor-large" /></template>
<style>
.ijtl6r9ad {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 6.621q0-1.504 1.39-2.079t2.451.489l6.672 6.671q.842.844.386 1.945q-.456 1.102-1.649 1.103h-.17q-.41 0-.631.344t-.052.716l1.027 2.259q.34.747.048 1.515t-1.042 1.101q-1.805.803-2.622-.996l-1.127-2.479q-.159-.35-.536-.426q-.378-.075-.659.188l-.35.327q-.894.833-2.014.346q-1.121-.488-1.122-1.71z");
}

</style>
