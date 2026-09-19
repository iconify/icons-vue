<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="deica7xru"/><path class="vicl1wbew"/><path class="zimjb5bkf"/><path class="z61u1fb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-palestinian-territories" /></template>
<style>
.deica7xru {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M1 25h63v14H1z");
}

.vicl1wbew {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M32.416 32L4.486 11.5C1.513 13.407 0 16.942 0 21v22c0 3.883 1.385 7.289 4.11 9.246l28.344-20.219z");
}

.z61u1fb2h {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M54 10H10c-2.201 0-4.03.553-5.514 1.5L22.879 25h41.12v-4c0-6.075-3.373-11-10-11");
}

.zimjb5bkf {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M22.68 39L4.121 52.238C5.656 53.345 7.609 54 10 54h44c6.627 0 10-4.925 10-11v-4z");
}

</style>
