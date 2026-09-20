<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n7z282b-s"/><path class="nh3rybb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:high-heeled-shoe" /></template>
<style>
.n7z282b-s {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M35.447 32.12S34.349 34 32.573 34h-13.23c-3.635 0-4.391-4.179-7.604-10.605s-6.906-3.048-6.906-3.048L3.618 35H2.334s-.614-12.551-1.25-14.596c-1.445-4.65-.625-8.181-.625-8.181l8.018.543l10.1 15.524z");
}

.nh3rybb_w {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M30.449 26.497c-1.137-.31-1.874-.625-1.874-.625c-.512.534-1.231.625-1.874.625c-3.825 0-5.808-1.556-8.122-6.873C13.58 8.144 5.354 3.38 2.959 3.38C.408 3.38-1.004 15.251.46 15.251c4.607 0 8.415.928 11.119 3.749c4.043 4.217 5.513 13.12 8.117 13.12h15.752s.624-4.061-4.999-5.623");
}

</style>
