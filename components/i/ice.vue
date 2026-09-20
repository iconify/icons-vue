<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wc39opb1h"/><path class="hz0jv7g1c"/><path class="horh306bx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ice" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.horh306bx {
  fill: var(--svg-color--3fdcff, #3fdcff);
  d: path("m8.608 14.587l-3.234-.22l-.686 2.054L6.684 21h9.265l1.31-6.058l-2.84-4.225l-2.138-.765v.444l-3.673 4.185z");
}

.hz0jv7g1c {
  fill: var(--svg-color--21b3d3, #21b3d3);
  d: path("m17.456 20l-1.507.983l-3.612-10.952l-.174-3.498L9.857 3l3.656 2.734l1.052 2.008l2.098.827l2.65 6.086z");
}

.wc39opb1h {
  fill: var(--svg-color--66e2ff, #66e2ff);
  d: path("m4.923 10.493l.619 4.23l4.708.326l2.835-5.355l-1.249-4.354l-1.929-2.295h-.529L8.343 3.9L7.297 7.5z");
}

</style>
