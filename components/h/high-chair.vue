<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrnr92b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:high-chair" /></template>
<style>
.lrnr92b9d {
  fill: currentColor;
  d: path("m6 21l1-10.95l-.8-4.725q-.125-.65.313-1.488T8.45 3q1.475 0 2.588.95t1.362 2.4L12.85 9H17q.425 0 .713.288T18 10t-.288.713T17 11h-.9l.9 10h-2l-.175-2h-6.65L8 21zm2.35-4h6.275l-.175-2h-5.9zm.375-4h5.55l-.2-2H8.9z");
}

</style>
