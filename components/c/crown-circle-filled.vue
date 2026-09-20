<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGeT0WbOLz"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="d4q_x4vza"/><path class="ggmmqgcou"/><path clip-rule="evenodd" class="i3drmccms"/></g></mask></defs><circle mask="url(#SVGeT0WbOLz)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:crown-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.d4q_x4vza {
  fill-rule: evenodd;
  d: path("m18.267 12.928l-.367.234a3 3 0 0 1-4.107-.867L13 11.105l-.793 1.19a3 3 0 0 1-4.107.867l-.367-.234L8.542 16h8.916zM6.654 9.87c-.768-.488-1.736.219-1.504 1.099l1.654 6.286A1 1 0 0 0 7.77 18h10.458a1 1 0 0 0 .967-.745l1.654-6.286c.232-.88-.736-1.587-1.504-1.099l-2.52 1.604a1 1 0 0 1-1.369-.289l-1.625-2.437a1 1 0 0 0-1.664 0l-1.625 2.437a1 1 0 0 1-1.369.29z");
}

.ft5dv1b6b {
  fill: none;
}

.ggmmqgcou {
  d: path("M14 6.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m8 2a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-16 0a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.i3drmccms {
  fill-rule: evenodd;
  d: path("M7.5 19.25a1 1 0 0 1 1-1h9.251a1 1 0 1 1 0 2H8.5a1 1 0 0 1-1-1");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
