<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="e-h7g-w4e"/><path class="w0c15ob2k"/><path clip-rule="evenodd" class="uu8ahhb0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-network-fill" /></template>
<style>
.e-h7g-w4e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.5 9.5C20.5 14.194 16.694 18 12 18C7.306 18 3.5 14.194 3.5 9.5C3.5 4.806 7.306 1 12 1C16.694 1 20.5 4.806 20.5 9.5ZM13.991 3.311C13.364 3.109 12.695 3 12 3C11.305 3 10.636 3.109 10.009 3.311C9.162 4.952 8.671 6.716 8.537 8.5H5.576C5.526 8.826 5.5 9.16 5.5 9.5C5.5 9.84 5.526 10.174 5.576 10.5H8.537C8.671 12.284 9.162 14.048 10.009 15.689C10.636 15.891 11.305 16 12 16C12.695 16 13.364 15.891 13.991 15.689C14.324 15.044 14.602 14.38 14.825 13.703C15.169 12.658 15.382 11.583 15.463 10.5H18.424C18.474 10.174 18.5 9.84 18.5 9.5C18.5 9.16 18.474 8.826 18.424 8.5H15.463C15.329 6.716 14.838 4.952 13.991 3.311ZM13.456 8.5H10.544C10.686 6.89 11.17 5.3 12 3.832C12.83 5.3 13.314 6.89 13.456 8.5ZM10.544 10.5H13.456C13.379 11.371 13.203 12.236 12.925 13.078C12.69 13.793 12.381 14.494 12 15.168C11.17 13.7 10.686 12.11 10.544 10.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uu8ahhb0m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 20C12.828 20 13.5 20.672 13.5 21.5C13.5 22.328 12.828 23 12 23C11.172 23 10.5 22.328 10.5 21.5C10.5 20.672 11.172 20 12 20Z");
  stroke: none;
}

.w0c15ob2k {
  d: path("M12 17V21.5M3 21.5H21");
}

</style>
