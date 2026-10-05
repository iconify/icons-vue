<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d_xyjvbfq"/><path clip-rule="evenodd" class="n3lc5blbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:houses-duotone" /></template>
<style>
.d_xyjvbfq {
  stroke-opacity: 0.4;
  d: path("M2 6.6149L5.7072 3.474C6.4532 2.842 7.5468 2.842 8.2928 3.474L10.363 5.2279M4 4.9204L4 10.6085");
}

.n3lc5blbl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.0604 7.71092C13.1794 6.76308 14.8204 6.76297 15.9393 7.71092L22.6463 13.3935C23.0675 13.7505 23.1193 14.3814 22.7625 14.8027C22.4056 15.224 21.7747 15.2767 21.3534 14.9199L20.9998 14.6201V19C20.9997 20.6567 19.6566 21.9999 17.9998 22H16.9998V18C16.9998 16.3431 15.6567 15 13.9998 15C12.343 15 10.9998 16.3431 10.9998 18V22H9.99985C8.34303 22 6.99995 20.6568 6.99985 19V14.6201L6.64633 14.9199C6.22498 15.2768 5.59414 15.224 5.23715 14.8027C4.88017 14.3813 4.93199 13.7505 5.35336 13.3935L12.0604 7.71092Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
