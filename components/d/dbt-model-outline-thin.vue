<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tks4a4biu"/><path class="pt-3kkb2k"/><path class="ae0h5kb0o"/><path class="ap-9ro6ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dbt-model-outline-thin" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.ap-9ro6ho {
  d: path("m8 17 2 2 4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.tks4a4biu {
  d: path("M13 3H6v18h12V8Z");
}

</style>
