<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d98c6mb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:candle-sharp" /></template>
<style>
.d98c6mb2h {
  fill: currentColor;
  d: path("M10.49 6.97q-.636-.664-.586-1.595q.05-1.05.71-1.864q.661-.815 1.444-1.511q.783.696 1.443 1.51t.71 1.846q.05.95-.583 1.615q-.634.664-1.567.664t-1.57-.665m10.172 9.827q.337-.337.337-.826t-.337-.826t-.817-.337t-.816.337t-.338.826t.338.826t.816.338t.817-.338M17.693 21H6.422q-1.01 0-1.716-.707T4 18.577v-1.443h5.673V9.5h4.77v7.635h3.638q-.185-.258-.287-.55t-.102-.623q0-.901.627-1.528t1.527-.626t1.527.626t.627 1.528q0 .834-.543 1.444q-.544.61-1.342.706v.465q0 1.01-.706 1.716T17.692 21");
}

</style>
