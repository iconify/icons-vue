<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_fd__bor"/><path class="fs7rqstiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:esports-trophy" /></template>
<style>
.d_fd__bor {
  d: path("M12.166 12.506q-.507.244-1.055.369Q10.562 13 10 13q-.123 0-.245-.006q-.123-.006-.245-.018t-.244-.03t-.241-.042q-.121-.024-.24-.054t-.236-.065q-.118-.036-.233-.077q-.116-.042-.229-.089q-.114-.047-.225-.099t-.219-.11t-.214-.121t-.207-.132t-.2-.141t-.194-.151t-.186-.16q-.091-.083-.178-.169q-.086-.087-.169-.178q-.082-.091-.16-.186t-.151-.194t-.141-.2q-.069-.102-.132-.207q-.063-.106-.121-.214t-.11-.219t-.099-.225q-.047-.113-.089-.229q-.041-.115-.077-.233q-.035-.117-.065-.236t-.054-.24q-.024-.12-.042-.241q-.018-.122-.03-.244t-.018-.245T5 8V3.5h10V8q0 .264-.028.527t-.083.521t-.138.509t-.19.492q-.108.241-.241.469q-.134.228-.29.441t-.334.409t-.376.37");
}

.fs7rqstiu {
  d: path("M5 5.5H3V7a3 3 0 0 0 2.5 3M15 5.5h2V7a3 3 0 0 1-2.5 3M10 13v5m-2.25 0h4.4M15 14.5h6.5V19H15Zm3.25 4.5v2.5m-2 0h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
