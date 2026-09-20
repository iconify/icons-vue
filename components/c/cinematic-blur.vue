<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8029mbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cinematic-blur" /></template>
<style>
.z8029mbtu {
  fill: currentColor;
  d: path("m4.616 4l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3h1.769q.69 0 1.153.463T21 5.616v12.769q0 .69-.462 1.153T19.385 20H4.615q-.69 0-1.152-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4m4.077 13.116h6.616v-.166q0-.792-.937-1.313q-.937-.522-2.371-.522t-2.371.521t-.937 1.314zm4.374-4.05q.434-.433.434-1.066t-.434-1.066T12 10.5t-1.066.434Q10.5 11.367 10.5 12t.434 1.066T12 13.5t1.066-.434");
}

</style>
