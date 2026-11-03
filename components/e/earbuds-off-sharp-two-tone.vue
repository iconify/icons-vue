<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="j3jbhmy6x"/><path class="asx9dyqwg"/><path class="b1ccuc1pd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earbuds-off-sharp-two-tone" /></template>
<style>
.asx9dyqwg {
  fill: currentColor;
  d: path("M19 7C19 7.5523 18.5523 8 18 8C17.4477 8 17 7.5523 17 7C17 6.4477 17.4477 6 18 6C18.5523 6 19 6.4477 19 7Z");
  stroke: none;
}

.b1ccuc1pd {
  d: path("M3.7159 3.7159C2.6787 4.4386 2 5.6401 2 7C2 9.2091 3.7909 11 6 11L6 19C6 20.1046 6.8954 21 8 21C9.1046 21 10 20.1046 10 19L10 10M14 14L14 19C14 20.1046 14.8954 21 16 21C17.1046 21 18 20.1046 18 19L18 18M6 17L10 17M14 17L17 17M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j3jbhmy6x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 11L11 19C11 20.6569 9.6569 22 8 22C6.3431 22 5 20.6569 5 19L5 11.899C2.6718 11.4241 0.9994 9.3762 0.9994 7C0.9994 5.4261 1.7406 3.944 2.9998 2.9998L11 11ZM19 19C19 20.6569 17.6569 22 16 22C14.3431 22 13 20.6569 13 19L13 13L19 19ZM5.7488 2.0062C5.8324 2.002 5.9161 1.9999 5.9998 1.9999C8.7613 1.9999 11 4.2385 11 7L11 7.2574L5.7488 2.0062ZM13 9.2574L13 7C13 4.2385 15.2386 1.9999 18.0001 1.9999C20.7615 1.9999 23.0001 4.2385 23.0001 6.9999C23.0001 9.376 21.328 11.4238 19 11.899L19 15.2574L13 9.2574Z");
  stroke: none;
}

</style>
