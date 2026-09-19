<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wtsuiuzir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coldshower-pro" /></template>
<style>
.wtsuiuzir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24V2.5m-3.099 1.196L24 6.795m-5.46.606L24 11.759m3.099-8.063L24 6.795m5.46.606L24 11.759M24 24L8.797 8.797m-1.345 3.037h4.382m-3.432 4.289l6.942-.779m-3.51-7.892v4.382m4.289-3.432l-.779 6.942M24 24H2.5m1.196 3.099L6.795 24m.606 5.46L11.759 24m-8.063-3.099L6.795 24m.606-5.46L11.759 24M24 24L8.797 39.203m3.037 1.345v-4.382m4.289 3.432l-.779-6.942m-7.892 3.51h4.382m-3.432-4.289l6.942.779M24 24v21.5m3.099-1.196L24 41.205m5.46-.606L24 36.241m-3.099 8.063L24 41.205m-5.46-.606L24 36.241M24 24l15.203 15.203m1.345-3.037h-4.382m3.432-4.289l-6.942.779m3.51 7.892v-4.382m-4.289 3.432l.779-6.942M24 24h21.5m-1.196-3.099L41.205 24m-.606-5.46L36.241 24m8.063 3.099L41.205 24m-.606 5.46L36.241 24M24 24L39.203 8.797m-3.037-1.345v4.382m-4.289-3.432l.779 6.942m7.892-3.51h-4.382m3.432 4.289l-6.942-.779");
}

</style>
