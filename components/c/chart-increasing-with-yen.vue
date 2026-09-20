<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG4hTDM8QP" class="chdp54bpl"/></defs><path class="cuy5ac7ov"/><path class="m0kgkmred"/><path class="m-c73dlzp"/><use href="#SVG4hTDM8QP" class="e0ty9gbgt"/><path class="m-6fi_b7x"/><use href="#SVG4hTDM8QP" class="pfsdhbbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:chart-increasing-with-yen" /></template>
<style>
.chdp54bpl {
  fill: var(--svg-color--abc884, #abc884);
  d: path("M40.16 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
}

.cuy5ac7ov {
  fill: var(--svg-color--689f38, #689f38);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.m-6fi_b7x {
  fill: var(--svg-color--efebe9, #efebe9);
  d: path("m41.26 39.36l10.3-22.2c.3-.61.92-1 1.6-1h5.1c.6 0 1.08.48 1.09 1.07c0 .15-.03.29-.09.43l-12.2 24c-.24.54.01 1.17.55 1.41c.11.05.23.08.35.09h6.9c.64-.02 1.18.48 1.2 1.12v2.38c.02.64-.48 1.18-1.12 1.2h-9.98c-.55 0-1 .45-1 1v4.1c0 .55.45 1 1 1h9.9c.64-.02 1.18.48 1.2 1.12v2.28c.02.64-.48 1.18-1.12 1.2h-9.98c-.55 0-1 .45-1 1v9.7c-.01.71-.59 1.29-1.3 1.3h-4.6c-.71-.01-1.29-.59-1.3-1.3v-9.7c0-.55-.45-1-1-1h-9.7c-.64.02-1.18-.48-1.2-1.12v-2.28c-.02-.64.48-1.18 1.12-1.2h9.78c.55 0 1-.45 1-1v-4.1c0-.55-.45-1-1-1h-9.7c-.64.02-1.18-.48-1.2-1.12v-2.38c-.02-.64.48-1.18 1.12-1.2h7.08a.997.997 0 0 0 1.03-.97a.97.97 0 0 0-.13-.53l-12.2-24c-.28-.48-.12-1.09.35-1.37c.2-.12.42-.16.65-.13h5.2c.68 0 1.3.39 1.6 1l10.3 22.2c.18.39.63.56 1.02.38c.17-.07.3-.21.38-.38");
}

.m-c73dlzp {
  fill: none;
  stroke: var(--svg-color--efebe9, #efebe9);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m11.56 110.86l12-14.8l12 8.4l7.9-16.5l12-8l12.1 20l10-28l11.7 18l14.1-25.9l7.9-40.2");
}

.m0kgkmred {
  fill: var(--svg-color--7cb342, #7cb342);
  d: path("M110.16 3.96h-98.2a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.46c.09-4.05-3.13-7.41-7.18-7.5z");
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
