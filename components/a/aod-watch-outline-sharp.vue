<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm88u38vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:aod-watch-outline-sharp" /></template>
<style>
.jm88u38vc {
  fill: currentColor;
  d: path("M9.308 11.5v-.885h5.384v.885zm1 2.385V13h3.384v.885zM10.73 4h2.538zm0 16h2.538zm-.77 1l-1.119-3.934q-1.258-.739-2.05-2.087T6 12t.792-2.979t2.05-2.087L9.962 3h4.077l1.119 3.935q1.258.738 2.05 2.086T18 12t-.792 2.979t-2.05 2.087L14.038 21zm5.577-5.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463m-5.476-9.21q.519-.163.991-.248T12 5.994t.947.085t.991.248L13.27 4h-2.538zM10.73 20h2.538l.67-2.327q-.52.164-.992.236T12 17.98t-.947-.072t-.991-.236z");
}

</style>
