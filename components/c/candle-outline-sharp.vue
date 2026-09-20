<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnv8vccfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:candle-outline-sharp" /></template>
<style>
.wnv8vccfl {
  fill: currentColor;
  d: path("M6.423 20h11.27q.604 0 1.013-.41q.41-.408.41-1.013v-.443H5v.443q0 .605.41 1.014q.408.409 1.013.409m4.068-13.03q-.637-.664-.587-1.595q.05-1.05.71-1.865q.661-.814 1.444-1.51q.783.696 1.443 1.51t.71 1.846q.05.95-.583 1.615q-.634.664-1.567.664t-1.57-.665m.182 10.165h2.77V10.5h-2.77zm2.21-10.848q.329-.348.329-.85q0-.618-.372-1.112q-.373-.494-.782-.954q-.41.46-.782.954t-.372 1.112q0 .502.327.85q.326.348.825.348q.5 0 .828-.348m7.779 10.51q.337-.337.337-.826t-.337-.826t-.817-.337t-.816.337t-.338.826t.338.826t.816.338t.817-.338M17.693 21H6.422q-1.01 0-1.716-.707T4 18.577v-1.443h5.673V9.5h4.77v7.635h3.638q-.185-.258-.287-.55t-.102-.623q0-.901.627-1.528t1.527-.626t1.527.626t.627 1.528q0 .834-.543 1.444q-.544.61-1.342.706v.465q0 1.01-.706 1.716T17.692 21m-7.019-3.866h2.77zm1.385-12.138");
}

</style>
