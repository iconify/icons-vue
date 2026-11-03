<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="qzch2p0fv"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earbuds-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qzch2p0fv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 11L11 16L5 16L5 11.899C2.6718 11.4241 0.9994 9.3762 0.9994 7C0.9994 5.4261 1.7406 3.944 2.9998 2.9998L11 11ZM19 19C19 20.6569 17.6569 22 16 22C14.3431 22 13 20.6569 13 19L13 18L18 18L19 19ZM5 18L11 18L11 19C11 20.6569 9.6569 22 8 22C6.3431 22 5 20.6569 5 19L5 18ZM5.6677 2.0109C5.7782 2.0035 5.889 1.9998 5.9997 1.9998C8.7612 1.9998 10.9999 4.2385 11 7L11 7.3431L5.6677 2.0109ZM13 9.3431L13 7C13 4.2385 15.2386 1.9999 18.0001 1.9999C20.7615 1.9999 23.0001 4.2385 23.0001 6.9999C23.0001 9.376 21.328 11.4238 19 11.899L19 15.3431L13 9.3431ZM19 7C19 6.4477 18.5523 6 18 6C17.4477 6 17 6.4477 17 7C17 7.5523 17.4477 8 18 8C18.5523 8 19 7.5523 19 7Z");
  stroke: none;
}

</style>
