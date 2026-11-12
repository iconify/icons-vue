<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7zz7vboy"/><path class="ipogvcwzq"/><path class="nr35mg1ux"/><path class="i9yxaoc2b"/><path class="b1qrr3bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-play-bold-duotone" /></template>
<style>
.b1qrr3bxa {
  fill: currentColor;
  d: path("M18.1982 2.30371C19.1919 2.51314 19.9379 2.86754 20.5352 3.46484C21.3926 4.32248 21.7483 5.48613 21.8955 7.25H14.9004L18.1982 2.30371Z");
}

.i9yxaoc2b {
  fill: currentColor;
  d: path("M11.999 2C13.8441 2 15.3284 2.00009 16.5391 2.08789L13.0977 7.25H8.40039L11.9004 2H11.999Z");
}

.ipogvcwzq {
  fill: currentColor;
  d: path("M10.5 11.6045C11.0004 11.2866 11.6716 11.719 13.0137 12.585C14.3377 13.4392 15 13.8666 15 14.5C15 15.1334 14.3377 15.5608 13.0137 16.415C11.6716 17.281 11.0004 17.7134 10.5 17.3955C9.99968 17.0776 10 16.2185 10 14.5C10 12.7815 9.99968 11.9224 10.5 11.6045Z");
}

.nr35mg1ux {
  fill: currentColor;
  d: path("M6.59766 7.25H2.10352C2.25076 5.48602 2.60632 4.32249 3.46387 3.46484C4.7162 2.21251 6.62118 2.03116 10.0947 2.00488L6.59766 7.25Z");
}

.y7zz7vboy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 12C2 10.7632 2 9.68872 2.02644 8.75H21.9736C22 9.68872 22 10.7632 22 12C22 16.714 22 19.071 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.071 2 16.714 2 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
