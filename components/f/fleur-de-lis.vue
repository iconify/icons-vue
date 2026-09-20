<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rdolr14sd"/><path class="hauijbc-m"/><path class="fs7yl0bqe"/><path class="h5sxovxxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:fleur-de-lis" /></template>
<style>
.fs7yl0bqe {
  fill: var(--svg-color--aa8dd8, #aa8dd8);
  d: path("M14 30c0-3.313 2.344-6 4-6s4 2.687 4 6s-4 6-4 6s-4-2.687-4-6");
}

.h5sxovxxv {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M25 24.5a3.5 3.5 0 0 1-3.5 3.5h-7a3.5 3.5 0 1 1 0-7h7a3.5 3.5 0 0 1 3.5 3.5");
}

.hauijbc-m {
  fill: var(--svg-color--aa8dd8, #aa8dd8);
  d: path("M13 10.227C13 3.951 18 0 18 0s5 3.951 5 10.227S20.762 25 18 25s-5-8.497-5-14.773");
}

.rdolr14sd {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M10.582 18c2.075 1.244 2.74 3.559 2.416 6h4.837A13 13 0 0 0 18 22c0-6.075-5.001-11.731-10.27-11.731c-8.479 0-9.866 9.043-4.567 11.731c-1.059-5 4.122-5.975 7.419-4m14.875 0c-2.075 1.244-2.74 3.559-2.416 6h-4.837a12.6 12.6 0 0 1-.165-2c0-6.075 5.001-11.731 10.269-11.731c8.479 0 9.866 9.043 4.567 11.731c1.061-5-4.121-5.975-7.418-4m4.334 8.647A3.49 3.49 0 0 1 26.5 29a3.49 3.49 0 0 1-3.449-3h-2.615A4.9 4.9 0 0 0 20 28c0 2.762 2.238 5 5 5s5-2.238 5-5c0-.472-.086-.92-.209-1.353M12.949 26A3.49 3.49 0 0 1 9.5 29a3.49 3.49 0 0 1-3.291-2.353A5 5 0 0 0 6 28c0 2.762 2.238 5 5 5s5-2.238 5-5c0-.715-.165-1.386-.436-2z");
}

</style>
