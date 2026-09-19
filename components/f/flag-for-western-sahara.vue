<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vubfsjbph"/><path class="rm8_wpbce"/><path class="k12m-svgc"/><path class="t3qrec6fg"/><path class="ceh7c3bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-western-sahara" /></template>
<style>
.ceh7c3bzt {
  fill: var(--svg-color--ec1c24, #ec1c24);
  fill-rule: evenodd;
  d: path("M34.37 27.906c-2.711.661-4.02 2.967-3.993 4.998c.025 2.305 1.573 4.356 3.981 4.923c-1.159.296-3.177-.207-4.438-1.686c-1.453-1.703-1.601-4.255-.331-6.104c1.247-1.818 3.387-2.419 4.781-2.131");
}

.k12m-svgc {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M54 11H10c-2.201 0-4.03.553-5.514 1.5L18.879 26h45.12v-4c0-6.075-3.373-11-10-11");
}

.rm8_wpbce {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M18.68 40L4.121 53.238C5.656 54.345 7.609 55 10 55h44c6.627 0 10-4.925 10-11v-4z");
}

.t3qrec6fg {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M26.416 33L4.486 12.5C1.513 14.407 0 17.942 0 22v22c0 3.883 1.385 7.289 4.11 9.246l22.344-20.219zm11.614-1.247l-2.627.004l-.816-2.657l-.809 2.657l-2.628-.004l2.13 1.619l-.827 2.638l2.138-1.64l2.139 1.64l-.827-2.638z");
}

.vubfsjbph {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M1 26h63v14H1z");
}

</style>
