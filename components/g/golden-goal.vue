<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bk9p3bb4a"/><path class="lsxab0c9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golden-goal" /></template>
<style>
.bk9p3bb4a {
  d: path("M11.864 13.998q-.121-.003-.241-.012t-.24-.024t-.238-.036t-.237-.047t-.234-.058t-.231-.07q-.114-.037-.227-.08t-.223-.092q-.111-.048-.219-.102t-.213-.112t-.208-.123t-.201-.132q-.099-.069-.195-.143t-.188-.151t-.18-.16t-.172-.169t-.164-.177t-.156-.184q-.075-.094-.146-.192t-.136-.199q-.066-.101-.127-.205q-.062-.104-.117-.211q-.056-.106-.107-.216q-.051-.109-.096-.221t-.086-.226q-.04-.113-.074-.229t-.063-.233t-.052-.235t-.041-.238q-.017-.119-.029-.239q-.011-.12-.017-.241Q7 9.121 7 9V3h10v6q0 .14-.008.28m-1.753 3.529q-.384.327-.825.57q-.442.243-.923.393");
}

.lsxab0c9d {
  d: path("M7 5H4.25v2.25a3.25 3.25 0 0 0 3 3.25M17 5h2.75v2.25q.001.335-.066.664q-.068.328-.201.636t-.326.582t-.439.503M12 17.9V21m-4 0h4.7m5.05-7l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
