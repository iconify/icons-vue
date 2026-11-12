<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dlqxafwlz"/><path class="vtqv6bbgc"/><path class="k2s1bueve"/><path class="y5p8pgh1d"/><path class="nszbcru_q"/><path class="auqpwjxps"/><path class="opk43_ukr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-list-broken" /></template>
<style>
.auqpwjxps {
  d: path("M11.5 7.5H10.5M17 7.5H14");
}

.dlqxafwlz {
  d: path("M10.5 11L17 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2s1bueve {
  d: path("M7 7.5H7.5");
}

.nszbcru_q {
  d: path("M13.5 14.5H10.5M17 14.5H16");
}

.opk43_ukr {
  d: path("M21 7V6.37006C21 5.17705 21 4.58055 20.842 4.09946C20.5425 3.18719 19.8468 2.47096 18.9606 2.16261C18.4933 2 17.9139 2 16.755 2H7.24502C6.08614 2 5.50671 2 5.03939 2.16261C4.15322 2.47096 3.45748 3.18719 3.15795 4.09946C3 4.58055 3 5.17705 3 6.37006V15M21 11V20.3742C21 21.2324 20.015 21.6878 19.3919 21.1176C19.0258 20.7826 18.4742 20.7826 18.1081 21.1176L17.625 21.5597C16.9834 22.1468 16.0166 22.1468 15.375 21.5597C14.7334 20.9726 13.7666 20.9726 13.125 21.5597C12.4834 22.1468 11.5166 22.1468 10.875 21.5597C10.2334 20.9726 9.26659 20.9726 8.625 21.5597C7.98341 22.1468 7.01659 22.1468 6.375 21.5597L5.8919 21.1176C5.52583 20.7826 4.97417 20.7826 4.6081 21.1176C3.985 21.6878 3 21.2324 3 20.3742V19");
}

.vtqv6bbgc {
  d: path("M7 11H7.5");
}

.y5p8pgh1d {
  d: path("M7 14.5H7.5");
}

</style>
