<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vubfsjbph"/><path class="ysesydbht"/><path class="jo3cxc2bm"/><path class="d-7nhublx"/><path class="w16vymtxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-jordan" /></template>
<style>
.d-7nhublx {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M54 11H10c-2.201 0-4.03.553-5.514 1.5L22.879 26h41.12v-4c0-6.075-3.373-11-10-11");
}

.jo3cxc2bm {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M22.68 40L4.121 53.238C5.656 54.345 7.609 55 10 55h44c6.627 0 10-4.925 10-11v-4z");
}

.vubfsjbph {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M1 26h63v14H1z");
}

.w16vymtxr {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.87 29.52l1.401-4.28l1.37 4.28l4.164-1.603l-2.461 3.728l3.87 2.287l-4.48.388l.61 4.451l-3.073-3.25l-3.091 3.25l.597-4.451l-4.448-.377l3.839-2.285l-2.474-3.741z");
}

.ysesydbht {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M32.416 33L4.486 12.5C1.513 14.407 0 17.942 0 22v22c0 3.883 1.385 7.289 4.11 9.246l28.344-20.219z");
}

</style>
