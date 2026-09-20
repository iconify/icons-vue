<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ocp6f9b4h"/><path class="r46rufpkx"/><path class="pc8q8_4-l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kmon-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ocp6f9b4h {
  fill: var(--svg-color--f231af, #f231af);
  d: path("M24 0H0v24h24z");
}

.pc8q8_4-l {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.47 17.943v1.371h-.008c-6.976 0-8.462-7.9-8.462-7.9l1.189-.329c0 1.756 2.496 6.858 7.053 6.858z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r46rufpkx {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.308 13.152l.9 2.546a.66.66 0 0 0 .824.384a.6.6 0 0 0 .407-.768l-.713-1.988l3.986 1.815c.343.155.754.027.919-.293a.626.626 0 0 0-.311-.86l-4.092-1.864l2.035-3.292c.183-.31.06-.704-.293-.868c-.352-.165-.8-.055-.987.256l-1.948 3.154l-.603-1.7a.66.66 0 0 0-.819-.385c-.333.105-.52.444-.411.768l.439 1.235v.023c-.018.594-.22 1.142-.814 1.142c-1.065 0-1.065-1.81-1.065-2.331c0-.517.389-4.037 4.878-4.037c4.494 0 5.984 3.84 5.984 6.007s-1.669 5.847-6.281 5.847c-.12 0-.979 1.372.22 1.372c4.031 0 7.437-3.283 7.437-7.338c0-.96-.284-3.588-2.652-5.554A6.92 6.92 0 0 0 12.7 4.686c-1.792 0-3.255.663-4.215 1.403c-2.011 1.555-2.13 3.913-2.13 4.357c0 1.056.608 3.383 2.432 3.383a1.83 1.83 0 0 0 1.522-.677");
}

</style>
