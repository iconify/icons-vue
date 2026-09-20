<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="es23ql25f"/><ellipse class="ut5f1zgmb"/><path class="xx-60bbvj"/><path class="vll4sjbkn"/><ellipse class="iz6w5ob-p"/><ellipse transform="rotate(-52.612 29.623 14.736)" class="dacj0vbtk"/><ellipse transform="rotate(-82.612 11.543 26.044)" class="ehr_6bcjf"/><ellipse transform="rotate(-52.612 36.736 31.264)" class="vvzmuf14u"/><path class="cwdd4mboe"/><path class="pu-bptcpe"/><ellipse class="k-b9_kbyl"/><ellipse class="u-zhcubak"/><ellipse transform="rotate(-29.313 21.041 19.724)" class="z32dypb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kick-the-buddy" /></template>
<style>
.cwdd4mboe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.786 9.076l4.255 6.417m1.947 3.404l6.717 11.577M15.88 21.707l4.139 7.346m16.717 4.591c0 .406 1.763 2.862 1.763 2.862M10.48 36.2l1.756-1.15s.723.5 1.18.262c.458-.238 3.12-1.91 3.12-1.91M12.81 28.45s-2.814.645-2.983 1.01c-.168.364-.168.725-.554.845c-.385.12-1.63.94-1.63.94l2.858 4.951m.721-12.77L5.5 13.917l4.269-2.347l3.361 5.223m.671 11.686l6.078 9.413m2.864-3.842l3.294 5.115l-3.167 2.247l-.278-.425m-.806-31.911l4.255-2.488l3.189 4.928m2.825 4.384L42.5 33.433l-4 3.072m-5.65-20.392c.174.05.718.659 1.362.222c.643-.436 4.106-2.523 4.106-2.523");
}

.dacj0vbtk {
  cx: 29.623px;
  cy: 14.736px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.769px;
  ry: 2.39px;
}

.ehr_6bcjf {
  cx: 11.543px;
  cy: 26.044px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.39px;
  ry: 3.769px;
}

.es23ql25f {
  cx: 26.037px;
  cy: 29.173px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.562px;
  ry: 5.683px;
}

.iz6w5ob-p {
  cx: 21.579px;
  cy: 39.361px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.441px;
  ry: 1.501px;
}

.k-b9_kbyl {
  cx: 21.144px;
  cy: 14.794px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.126px;
  ry: 1.105px;
}

.pu-bptcpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.053 22.611s.014-.877.534-1.31s4.552-2.81 4.552-2.81l-2.868-4.65");
}

.u-zhcubak {
  cx: 16.104px;
  cy: 17.099px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.299px;
  ry: 2.191px;
}

.ut5f1zgmb {
  cx: 19.229px;
  cy: 17.302px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.671px;
  ry: 5.304px;
}

.vll4sjbkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.208 23.035c.313.43 1.171 2.746 1.171 2.746m2.177-4.508c.337.169 1.397 1.762 1.397 1.762m7.102 7.295l2.243 1.156m-10.31 2.971l-.838 3.194");
}

.vvzmuf14u {
  cx: 36.736px;
  cy: 31.264px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.696px;
  ry: 1.71px;
}

.xx-60bbvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.386 18.346l-3.878 5.364m-8.66 3.175s5.42-.787 5.864-1.285");
}

.z32dypb1g {
  cx: 21.041px;
  cy: 19.724px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.082px;
  ry: 1.493px;
}

</style>
