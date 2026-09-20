<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikvw6bcoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:alarm-pause-sharp" /></template>
<style>
.ikvw6bcoh {
  fill: currentColor;
  d: path("M8.488 21.288q-1.638-.713-2.85-1.925t-1.925-2.85T3 13t.713-3.512t1.924-2.85t2.85-1.925T12 4t3.513.713t2.85 1.925t1.925 2.85T21 13t-.712 3.513t-1.925 2.85t-2.85 1.925T12 22t-3.512-.712M5.6 2.35L7 3.75L2.75 8l-1.4-1.4zm12.8 0l4.25 4.25l-1.4 1.4L17 3.75zM9 17h2V9H9zm4 0h2V9h-2z");
}

</style>
