<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_u8fobig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-tools" /></template>
<style>
.n_u8fobig {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.519 3.75q.167.004.316.079q.066.033.125.079q.058.045.107.101q.048.055.085.12q.036.064.06.134q.023.07.032.143t.004.147t-.025.145t-.052.137l-1.758 3.517l3.087 3.087l2.47-2.469q.102-.102.234-.159q.133-.057.277-.061q.149-.004.289.05t.247.157t.168.239t.065.285q.064 2.568-1.924 4.195q-1.822 1.491-4.077 1.136L8.03 21.031q-2.53 2.527-5.059-.002T2.97 15.97l6.218-6.219q-.355-2.255 1.136-4.077q1.627-1.988 4.195-1.924");
}

</style>
