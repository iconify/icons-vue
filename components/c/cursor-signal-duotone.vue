<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j2whz3qht"/><path class="oofikhb0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-signal-duotone" /></template>
<style>
.j2whz3qht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.33541 11.1582C8.98387 10.053 9.99387 9.02619 11.0805 9.30369L11.186 9.33396L22.0034 12.9375C23.2819 13.3639 23.3468 15.1486 22.101 15.666L17.6723 17.5029L15.4907 22.1601C14.9281 23.3592 13.1822 23.2485 12.7797 21.9834L9.33541 11.1582Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oofikhb0u {
  d: path("M6 10C6 7.7909 7.7909 6 10 6M2 10C2 5.5817 5.5817 2 10 2");
}

</style>
