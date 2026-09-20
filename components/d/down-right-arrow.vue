<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qovi5mbkq"/><path class="taetzn2em"/><path class="hf_3lwbfw"/><path class="g_2zs9bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:down-right-arrow" /></template>
<style>
.g_2zs9bjv {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hf_3lwbfw {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M97.71 56.67v33.94a4.01 4.01 0 0 1-4.24 4.24H59.52c-3.46-.21-4.95-4.38-2.55-6.79l9.9-9.9c.78-.78.78-2.05 0-2.83L34.34 42.8a4.01 4.01 0 0 1 0-5.66L40 31.48a4.01 4.01 0 0 1 5.66 0l32.53 32.54c.78.78 2.05.78 2.83 0l9.9-9.9c2.4-2.4 6.58-.92 6.79 2.55");
}

.qovi5mbkq {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.4 0-8 3.6-8 8v104c0 4.4 3.6 8 8 8h104c4.4 0 8-3.6 8-8V12c0-4.4-3.6-8-8-8");
}

.taetzn2em {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5C7.4 4 4 7.4 4 11.5v97.9c0 4.2 3.4 7.5 7.5 7.5h98.1c4.2 0 7.5-3.4 7.5-7.5V11.5c.2-4.1-3.3-7.5-7.4-7.5");
}

</style>
