<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e061s5bkz"/><path class="kmlq93bxm"/><path class="xh228jcir"/><path class="nfclxdb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-off-broken" /></template>
<style>
.e061s5bkz {
  d: path("M20.6622 7C21.513 8.47087 22 10.1786 22 12C22 13.8777 21.4825 15.6346 20.5822 17.1357");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmlq93bxm {
  d: path("M17 3.33782C15.5291 2.48697 13.8214 2 12 2C10.1223 2 8.36541 2.51754 6.86429 3.41776");
}

.nfclxdb-l {
  d: path("M2 2L4.92893 4.92893L5.77811 5.77811L9.63753 9.63753L19.0711 19.0711L22 22");
}

.xh228jcir {
  d: path("M4.92915 4.92969C3.1195 6.73933 2.00021 9.23933 2.00021 12.0008C2.00021 13.6004 2.37583 15.1124 3.04367 16.4532C3.22115 16.8095 3.28022 17.2168 3.17733 17.6014L2.58172 19.8274C2.32317 20.7937 3.20723 21.6778 4.17356 21.4192L6.3996 20.8236C6.78415 20.7207 7.19142 20.7798 7.54774 20.9573C8.88858 21.6251 10.4005 22.0008 12.0002 22.0008C14.7616 22.0008 17.2616 20.8815 19.0713 19.0718");
}

</style>
