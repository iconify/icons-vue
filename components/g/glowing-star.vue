<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="y1rb3vk_h"><ellipse transform="rotate(-134.991 47.492 10.518)" class="w33b5zbup"/><path class="cu5fwyb5n"/><ellipse transform="rotate(-45.017 15.142 10.516)" class="vvk-25b9c"/><path class="rw9xfdb3g"/></g><path class="nlc6qbmhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:glowing-star" /></template>
<style>
.cu5fwyb5n {
  d: path("M8.838 40.42c-3.905 3.058-6.653 6.07-6.141 6.718c.512.653 4.093-1.293 7.992-4.351c3.905-3.057 6.656-6.06 6.144-6.713c-.51-.656-4.088 1.293-7.995 4.346m46.018 0c3.904 3.058 6.654 6.07 6.143 6.718c-.512.653-4.093-1.293-7.992-4.351c-3.906-3.057-6.656-6.06-6.146-6.713c.51-.656 4.088 1.293 7.995 4.346M33.21 53.713c.003 4.953-.668 8.975-1.499 8.975c-.828.004-1.503-4.02-1.503-8.971c-.008-4.961.662-8.98 1.49-8.98c.831 0 1.504 4.02 1.512 8.976");
}

.nlc6qbmhe {
  fill: var(--svg-color--faec78, #faec78);
  d: path("m49.44 23.23l-12.41-2.283l-5.86-10.422l-5.86 10.422l-11.958 2.413l8.336 10.11l-2.185 13.469l11.667-5.737l11.99 5.86l-2.506-13.592z");
}

.rw9xfdb3g {
  d: path("m56.28 20.523l-19.25-.091L31.17.959l-5.86 19.473l-19.25.091l15.628 12.433l-7.902 21.2L31.17 40.685l17.385 13.471l-7.901-21.2z");
}

.vvk-25b9c {
  cx: 15.14px;
  cy: 10.518px;
  rx: 1.502px;
  ry: 8.976px;
}

.w33b5zbup {
  cx: 47.49px;
  cy: 10.518px;
  rx: 1.502px;
  ry: 8.976px;
}

.y1rb3vk_h {
  fill: var(--svg-color--edc26e, #edc26e);
}

</style>
