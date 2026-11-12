<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ae217nbka"/><path class="u154v_8wc"/><path class="v5w4uik1f"/><path class="sdqne7jvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:broom-broken" /></template>
<style>
.ae217nbka {
  d: path("M12.728 5.53569C14.2901 3.97359 16.8227 3.97351 18.3848 5.53561");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sdqne7jvy {
  d: path("M18.2526 16C18.1966 16.2465 18.1329 16.4973 18.0604 16.7509C17.7886 17.7018 17.3602 18.6587 16.9094 19.5125C15.9553 21.3194 13.7459 21.8797 12.0375 21.0076L10.9412 20.3407C7.93376 18.5111 5.40928 15.9867 3.57976 12.9792L2.91289 11.883C2.04084 10.1746 2.60107 7.96516 4.40797 7.01113C5.26178 6.56032 6.2187 6.13191 7.16958 5.86007C10.0291 5.04261 12.535 5.34235 12.535 5.34235L18.3851 11.1925");
}

.u154v_8wc {
  d: path("M18.3848 5.53564C19.9469 7.09774 19.9469 9.63048 18.3848 11.1926");
}

.v5w4uik1f {
  d: path("M20.5061 3.41431L18.3848 5.53563");
}

</style>
