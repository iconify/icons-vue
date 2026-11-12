<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bmt38ebpo"/><path class="qvtciobpz"/><path class="r2xy8db8f"/><path class="dyng1obou"/><path class="kodu4vb2q"/><path class="ymq-tib4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-wave-broken" /></template>
<style>
.bmt38ebpo {
  d: path("M13.2633 4.6551C14.4211 5.47731 15 5.88842 15 6.45874C15 7.02907 14.4211 7.44017 13.2633 8.26238L8 12V5.22457C8 3.33816 8 2.39496 8.60465 2.08561C8.96658 1.90043 9.38847 2.02253 10 2.38554");
}

.dyng1obou {
  d: path("M3 8.5L8 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kodu4vb2q {
  d: path("M19 5C19 5 21 7.1 21 12C21 12.7276 20.9559 13.3936 20.8808 14M19.6755 18C19.3043 18.6805 19 19 19 19");
}

.qvtciobpz {
  d: path("M11.5253 20.5791L13.2633 19.3449C14.4211 18.5227 15 18.1116 15 17.5413C15 16.9709 14.4211 16.5598 13.2633 15.7376L8 12V18.7754C8 20.6618 8 21.605 8.60465 21.9144C9.2093 22.2238 9.98131 21.6755 11.5253 20.5791Z");
}

.r2xy8db8f {
  d: path("M3 15.5L8 12");
}

.ymq-tib4j {
  d: path("M17 8C17 8 18 9.9 18 12C18 14.1 17 16 17 16");
}

</style>
