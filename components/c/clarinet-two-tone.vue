<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t0n18mqtf"/><path class="rj6bnccub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clarinet-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rj6bnccub {
  d: path("M8 14H6.1547C6.0522 14 5.9503 13.9842 5.8525 13.9533L2.6978 12.9533C1.7674 12.6583 1.7674 11.3417 2.6978 11.0467L5.8525 10.0467C5.9503 10.0158 6.0522 10 6.1547 10H8H15C18 10 19.2322 8.3536 20.2929 7.2929C20.4804 7.1054 20.7348 7 21 7C21.5523 7 22 7.4477 22 8V16C22 16.5523 21.5523 17 21 17C20.7348 17 20.4804 16.8946 20.2929 16.7071C19.2322 15.6464 18 14 15 14ZM9 10V7.5M13 10V7.5");
}

.t0n18mqtf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12L23 16C23 17.1046 22.1046 18 21 18C20.4695 18 19.9608 17.7892 19.5858 17.4142C19.2526 17.081 19.0742 16.8761 18.7425 16.5529C18.4563 16.2741 18.1576 16.0138 17.8187 15.7876C17.1614 15.3491 16.2954 15 15 15L8 15L6.1547 15C5.9494 15 5.7459 14.9684 5.5512 14.9068L2.3956 13.9066C1.9495 13.7651 1.5916 13.4906 1.3498 13.1381C1.1125 12.7922 1 12.3911 1 12C1 11.6089 1.1125 11.2078 1.3498 10.8619C1.5916 10.5094 1.9495 10.2349 2.3956 10.0935L5.5503 9.0934C5.7459 9.0316 5.9494 9 6.1547 9L8 9L15 9C16.2954 9 17.1614 8.6509 17.8187 8.2124C18.1576 7.9862 18.4563 7.7259 18.7425 7.4471C19.0742 7.1239 19.2526 6.919 19.5858 6.5858C19.9608 6.2108 20.4695 6 21 6C22.1046 6 23 6.8954 23 8Z");
  stroke: none;
}

</style>
