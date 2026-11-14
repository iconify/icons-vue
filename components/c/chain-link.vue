<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdx93d87o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chain-link" /></template>
<style>
.mdx93d87o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 7.75h2q1.76 0 3.005 1.245q.467.466.758 1.005H10.25q-2 0-2 2t2 2h1.513q-.291.539-.758 1.005Q9.76 16.25 8 16.25H6q-1.76 0-3.005-1.245T1.75 12t1.245-3.005T6 7.75M12.237 14q.291.539.758 1.005Q14.24 16.25 16 16.25h2q1.76 0 3.005-1.245T22.25 12t-1.245-3.005T18 7.75h-2q-1.76 0-3.005 1.245q-.467.466-.758 1.005h1.513q2 0 2 2t-2 2z");
}

</style>
