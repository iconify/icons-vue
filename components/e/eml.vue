<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGInT9ijIK)" class="cujlh_vgi"/><path fill="url(#SVGJsxx1cZT)" class="kar31qbjl"/><defs><linearGradient id="SVGInT9ijIK" x1="5.894" x2="15.401" y1="7.499" y2="17.889" gradientUnits="userSpaceOnUse"><stop class="d45rsrbzp"/><stop offset="1" class="o_w89tbpe"/></linearGradient><linearGradient id="SVGJsxx1cZT" x1="12.3" x2="19.67" y1="11.705" y2="17.735" gradientUnits="userSpaceOnUse"><stop class="myebd9bcg"/><stop offset="1" class="e2617_eqa"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eml" /></template>
<style>
.cujlh_vgi {
  d: path("M7.5 14.05A4.45 4.45 0 0 1 3 9.65a4.45 4.45 0 0 1 4.5-4.4a4.49 4.49 0 0 1 4.3 3.1c.485 1.535.8 1.89.2 4.53c0 1.175.1 2.25.3 2.935c-.6-.585-1.08-2.05-1.8-2.05c-1.015 0-2 .29-3 .29z");
}

.d45rsrbzp {
  stop-color: var(--svg-color--6db82b, #6db82b);
}

.e2617_eqa {
  stop-color: var(--svg-color--71c6e3, #71c6e3);
}

.ft5dv1b6b {
  fill: none;
}

.kar31qbjl {
  d: path("M15.095 10.165c-.8.075-1.605.065-1.895-.22c-.48-.47-1.2-1.37-1.5-1.76c.2.49.6 1.645.6 2.35c0 .28-.09.71-.2 1.205c-.635 3.01.33 7.01 4.4 7.01c2.485 0 4.5-1.97 4.5-4.4a4.45 4.45 0 0 0-2.793-4.08a4.5 4.5 0 0 0-1.707-.32c-.49 0-.965.075-1.405.215");
}

.myebd9bcg {
  stop-color: var(--svg-color--4683c3, #4683c3);
}

.o_w89tbpe {
  stop-color: var(--svg-color--c9d808, #c9d808);
}

</style>
