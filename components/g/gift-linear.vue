<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oyjqk5bct"/><path class="dxon-mtqm"/><path class="o6zz0vbkl"/><path class="mzn_blbqr"/><path class="dadlzrowr"/><path class="raokm3b8s"/><path class="xvjk-cbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gift-linear" /></template>
<style>
.dadlzrowr {
  d: path("M12 12.0001H13.9649C15.4548 12.0001 16.7535 10.9861 17.1148 9.5407C17.5158 7.93697 16.0631 6.48431 14.4594 6.88524C13.014 7.24659 12 8.54529 12 10.0352V12.0001Z");
}

.dxon-mtqm {
  d: path("M12 2V22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzn_blbqr {
  d: path("M11 12C11 14.2091 9.20914 16 7 16");
}

.o6zz0vbkl {
  d: path("M13 12C13 14.2091 14.7909 16 17 16");
}

.oyjqk5bct {
  d: path("M22 12H2");
}

.raokm3b8s {
  d: path("M12.0001 12.0001H10.0352C8.54529 12.0001 7.24659 10.9861 6.88524 9.5407C6.48431 7.93697 7.93698 6.48431 9.5407 6.88524C10.9861 7.24659 12.0001 8.54529 12.0001 10.0352V12.0001Z");
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

</style>
