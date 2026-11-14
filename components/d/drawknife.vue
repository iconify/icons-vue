<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_pys_blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drawknife" /></template>
<style>
.k_pys_blo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.592 4.82q-.595-.849-1.615-1.029t-1.868.415T4.081 5.82L2.258 16.159q-.18 1.02.414 1.869q.594.848 1.614 1.029t1.868-.414t1.029-1.615L8.43 9.951l.347 1.25q.017.059.042.114t.06.106t.077.095t.09.081t.103.066q.054.028.112.048q.057.019.118.029t.121.01h5q.061 0 .121-.01q.061-.01.118-.029q.058-.02.112-.048q.054-.029.103-.066t.09-.081q.042-.045.077-.095t.06-.106t.042-.114l.347-1.25l1.247 7.077q.18 1.02 1.029 1.615q.848.594 1.868.414q1.02-.181 1.614-1.029q.594-.849.414-1.868L19.919 5.82q-.18-1.02-1.028-1.614t-1.868-.415t-1.615 1.029q-.309.442-.408.93H9q-.099-.488-.408-.93");
}

</style>
