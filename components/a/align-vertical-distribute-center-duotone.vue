<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t27ni-g8u"/><path class="ffga4kdqe"/><path class="txvv4ubsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-center-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ffga4kdqe {
  d: path("M7 16C7.5523 16 8 16.448 8 17C8 17.552 7.5523 18 7 18H2C1.4477 18 1 17.552 1 17C1 16.448 1.4477 16 2 16H7ZM22 16C22.5523 16 23 16.448 23 17C23 17.552 22.5523 18 22 18H17C16.4477 18 16 17.552 16 17C16 16.448 16.4477 16 17 16H22ZM5 6C5.5523 6 6 6.448 6 7C6 7.552 5.5523 8 5 8H2C1.4477 8 1 7.552 1 7C1 6.448 1.4477 6 2 6H5Z");
}

.t27ni-g8u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 13C16.6555 13 18 14.344 18 16V18C18 19.659 16.6553 21 15 21H9C7.3422 21 6 19.658 6 18V16C6 14.345 7.3411 13 9 13H15ZM17 3C18.6519 3 20 4.341 20 6V8C20 9.656 18.6545 11 17 11H7C5.3415 11 4 9.661 4 8V6C4 4.349 5.3375 3 7 3H17Z");
}

.txvv4ubsi {
  d: path("M22 6C22.5523 6 23 6.448 23 7C23 7.552 22.5523 8 22 8H19C18.4477 8 18 7.552 18 7C18 6.448 18.4477 6 19 6H22Z");
}

</style>
