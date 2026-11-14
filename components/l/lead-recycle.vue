<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ofgfj922j"/><path class="f7gqvkbki"/><path class="jweqlabrt"/><path class="vr4ci77ox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lead-recycle" /></template>
<style>
.f7gqvkbki {
  d: path("M12 21.5A9.5 9.5 0 0 1 5.282 5.282");
}

.jweqlabrt {
  d: path("M5.25 8V5.25H2.5M12 2.5a9.5 9.5 0 0 1 6.718 16.218");
}

.ofgfj922j {
  d: path("M9.75 8.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8.25 17a3.75 3.75 0 0 1 7.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vr4ci77ox {
  d: path("M18.75 16v2.75h2.75");
}

</style>
