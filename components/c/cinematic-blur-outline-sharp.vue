<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l16_93pkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cinematic-blur-outline-sharp" /></template>
<style>
.l16_93pkg {
  fill: currentColor;
  d: path("m4.616 4l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3H21v16H3V4zM4 8v11h16V8zm0 0v11zm4.692 9.116h6.616v-.166q0-.792-.937-1.313q-.937-.522-2.371-.522t-2.371.521t-.937 1.314zm4.374-4.05q.434-.433.434-1.066t-.434-1.066T12 10.5t-1.066.434Q10.5 11.367 10.5 12t.434 1.066T12 13.5t1.066-.434");
}

</style>
