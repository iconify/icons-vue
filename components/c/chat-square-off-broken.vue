<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="re4elkb7b"/><path class="zg90ki5is"/><path class="rqx2gjabx"/><path class="rjy1xybnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-off-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.re4elkb7b {
  d: path("M18.6999 18.6997C18.0819 18.9086 17.3335 18.9721 16.2106 18.9915C15.3603 19.0061 14.9351 19.0135 14.5974 19.2099C14.2597 19.4063 14.0495 19.7615 13.629 20.4719L13.0869 21.3877C12.6037 22.204 11.3967 22.204 10.9136 21.3877L10.3715 20.4719C9.95098 19.7615 9.74075 19.4063 9.40305 19.2099C9.06535 19.0135 8.64018 19.0061 7.78984 18.9915C6.53448 18.9699 5.74715 18.8929 5.08684 18.6194C3.8617 18.112 2.88833 17.1386 2.38086 15.9135");
}

.rjy1xybnj {
  d: path("M5.68164 2.23868C6.77528 2 8.25144 2 10.4996 2H13.4996C16.773 2 18.4097 2 19.6121 2.7368C20.2849 3.14908 20.8505 3.71473 21.2628 4.38751C21.9996 5.58985 21.9996 7.22657 21.9996 10.5V11.5C21.9996 13.8297 21.9996 14.9946 21.619 15.9134C21.406 16.4275 21.1111 16.8973 20.7499 17.3069");
}

.rqx2gjabx {
  d: path("M2 2L3.46447 3.46447L4.92893 4.92893L5.77811 5.77811L9.63753 9.63753L18.6996 18.6996L19.0711 19.0711L22 22");
}

.zg90ki5is {
  d: path("M3.46447 3.46448C3.18742 3.74152 2.94294 4.05113 2.7368 4.38752C2 5.58987 2 7.22658 2 10.5");
}

</style>
