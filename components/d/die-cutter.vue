<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnh9u7dfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:die-cutter" /></template>
<style>
.cnh9u7dfe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 2.25h-11q-1.76 0-3.005 1.245T2.25 6.5v11q0 1.76 1.245 3.005T6.5 21.75h11q1.76 0 3.005-1.245T21.75 17.5v-11q0-1.76-1.245-3.005T17.5 2.25m-4.061 5.704v.001l.388.904q.181.423.64.454l.958.064q1.014.068 1.328 1.035t-.467 1.617l-.82.684q-.368.307-.244.77l.261.98q.265.989-.557 1.601q-.822.613-1.695.074l-.838-.515q-.393-.242-.786 0l-.839.516q-.872.538-1.694-.075q-.822-.612-.556-1.603l.26-.978q.124-.463-.244-.77l-.82-.684q-.781-.651-.467-1.617q.314-.967 1.328-1.035l.958-.064q.459-.031.64-.453l.388-.906q.406-.949 1.439-.949t1.439.949");
}

</style>
