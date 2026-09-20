<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lta13l2ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:digital-wellbeing-sharp" /></template>
<style>
.lta13l2ti {
  fill: currentColor;
  d: path("M10.064 8.09q-.795-.794-.795-1.936t.795-1.937T12 3.423t1.937.794t.794 1.937t-.794 1.936T12 8.885t-1.936-.794M12 20.27l-5.461-5.462q-.385-.385-.577-.885t-.193-1.077q0-1.148.792-1.94q.791-.79 1.939-.79q.552 0 1.03.207q.478.208.882.611L12 12.523l1.589-1.588q.384-.385.871-.602t1.04-.217q1.148 0 1.94.79q.79.792.79 1.94q0 .577-.191 1.077t-.578.885z");
}

</style>
