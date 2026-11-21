<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="b6xukzm6h"/><path class="zr7uqqbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:beehouse-fill" /></template>
<style>
.b6xukzm6h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.8119 12.9538L2.8886 7.4144C2.8796 7.3601 2.875 7.3051 2.875 7.25C2.875 6.8411 3.1239 6.4734 3.5036 6.3215L10.8858 3.3686C11.601 3.0826 12.399 3.0826 13.1142 3.3686L20.4964 6.3215C20.8761 6.4734 21.125 6.8411 21.125 7.25C21.125 7.3051 21.1204 7.3601 21.1114 7.4144L19.2649 18.4932C19.0238 19.9398 17.7722 21 16.3057 21L7.6943 21C6.2278 21 4.9762 19.9398 4.7351 18.4932ZM10 9C9.4477 9 9 9.4477 9 10C9 10.5523 9.4477 11 10 11L14 11C14.5523 11 15 10.5523 15 10C15 9.4477 14.5523 9 14 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zr7uqqbpf {
  d: path("M2 8L11.2572 4.2971C11.734 4.1064 12.266 4.1064 12.7428 4.2971L22 8M12 4V2M12 20V22");
}

</style>
