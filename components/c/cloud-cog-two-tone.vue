<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s2crr3qqu"/><path class="hztwicecj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-cog-two-tone" /></template>
<style>
.hztwicecj {
  d: path("M14.6667 17C14.6667 18.4728 13.4728 19.6667 12 19.6667C10.5272 19.6667 9.3333 18.4728 9.3333 17C9.3333 15.5272 10.5272 14.3333 12 14.3333C13.4728 14.3333 14.6667 15.5272 14.6667 17ZM15.5417 17L16 17M14.5043 19.5043L14.8284 19.8284M12 20.5417L12 21M9.4957 19.5043L9.1716 19.8284M8.4583 17L8 17M9.4957 14.4957L9.1716 14.1716M12 13.4583L12 13M14.5043 14.4957L14.8284 14.1716");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s2crr3qqu {
  stroke-opacity: 0.4;
  d: path("M4 16.4641C2.7624 15.7496 2 14.4291 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.4291 21.2376 15.7496 20 16.4641");
}

</style>
