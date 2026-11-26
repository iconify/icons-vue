<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t8drw368i"/><path class="ox_05kl4h"/><path class="almkwob9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-three-eighth-two-tone" /></template>
<style>
.almkwob9v {
  fill: currentColor;
  d: path("M16.9498 7.0502C18.2154 8.3159 19 10.0672 19 12C19 13.8565 18.2625 15.637 16.9497 16.9497C16.7621 17.1373 16.5078 17.2426 16.2426 17.2426C15.9774 17.2426 15.723 17.1372 15.5355 16.9497L11.2929 12.7071C11.1054 12.5196 11 12.2652 11 12L11 6C11 5.4477 11.4477 5 12 5C13.9328 5 15.6841 5.7846 16.9498 7.0502Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox_05kl4h {
  d: path("M12 2C17.5228 2 22 6.4772 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2Z");
}

.t8drw368i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
  stroke: none;
}

</style>
