<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v31in3w2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-bus-outline-sharp" /></template>
<style>
.v31in3w2y {
  fill: currentColor;
  d: path("M6.539 20v-2.396q-.489-.212-1.014-.901T5 15.115V6q0-1.556 1.685-2.278Q8.369 3 12 3q3.762 0 5.38.694T19 6v9.116q0 .898-.525 1.587q-.525.69-1.014.9V20h-1.23v-2H7.769v2zm5.473-14.461h5.907H6.104zM16 12H6h12zM6 11h12V6.539H6zm3.293 4.293q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323m7 0q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323M6.103 5.54H17.92q-.26-.772-1.603-1.155Q14.973 4 12.012 4q-2.945 0-4.288.39q-1.343.389-1.62 1.149M8 17h8q.825 0 1.413-.587T18 15v-3H6v3q0 .825.588 1.413T8 17");
}

</style>
