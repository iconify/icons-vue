<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p7ojfcswp"/><path clip-rule="evenodd" class="kbgjwt7vt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-check-fill" /></template>
<style>
.kbgjwt7vt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 7L19 7C21.2091 7 23 8.7909 23 11L23 19C23 21.2091 21.2091 23 19 23L11 23C8.7909 23 7 21.2091 7 19L7 11C7 8.7909 8.7909 7 11 7ZM12.7071 14.2929C12.5196 14.1054 12.2652 14 12 14C11.4477 14 11 14.4477 11 15C11 15.2652 11.1054 15.5196 11.2929 15.7071L13.2929 17.7071C13.4804 17.8946 13.7348 18 14 18C14.2652 18 14.5196 17.8946 14.7071 17.7071L18.7071 13.7071C18.8946 13.5196 19 13.2652 19 13C19 12.4477 18.5523 12 18 12C17.7348 12 17.4804 12.1054 17.2929 12.2929L14 15.5858L12.7071 14.2929Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7ojfcswp {
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2L5 2C3.34315 2 2 3.34315 2 5L2 13C2 14.2714 2.8015 15.4046 4 15.8284");
}

</style>
