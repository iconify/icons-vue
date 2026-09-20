<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r4ne89boa"/><path class="uh344ob1x"/><ellipse class="lkpvfnbej"/><path class="flk_14b_x"/><ellipse class="fj3i_t73l"/><path class="hepizzbtj"/><ellipse class="o8zfk7bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:battery" /></template>
<style>
.fj3i_t73l {
  cx: 18px;
  cy: 3px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 10px;
  ry: 2px;
}

.flk_14b_x {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.956 12.788c.091.544-.321 1.066-.922 1.136c-.676.079-1.355.121-2.035.147V16a1 1 0 0 1-2 0v-1.93a26 26 0 0 1-2.035-.147c-.601-.07-1.012-.591-.922-1.136a1.04 1.04 0 0 1 1.152-.851c.6.07 1.202.109 1.804.133V10a1 1 0 0 1 2 0v2.07a25 25 0 0 0 1.804-.133a1.04 1.04 0 0 1 1.154.851m-1.652 17.746a21 21 0 0 1-4.607 0a1.05 1.05 0 0 0-1.153.854c-.091.544.326 1.067.934 1.134c1.676.184 3.368.184 5.044 0c.609-.067 1.026-.59.934-1.134a1.047 1.047 0 0 0-1.152-.854");
}

.hepizzbtj {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M14 1v1.5c0 .552 1.791 1 4 1s4-.448 4-1V1z");
}

.lkpvfnbej {
  cx: 18px;
  cy: 3px;
  fill: var(--svg-color--5c913b, #5c913b);
  rx: 12px;
  ry: 3px;
}

.o8zfk7bkw {
  cx: 18px;
  cy: 1px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 4px;
  ry: 1px;
}

.r4ne89boa {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M30 32.7c0 1.657-5.373 3.3-12 3.3S6 34.357 6 32.7S11.373 30 18 30s12 1.043 12 2.7");
}

.uh344ob1x {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M6 3h24v29.7H6z");
}

</style>
