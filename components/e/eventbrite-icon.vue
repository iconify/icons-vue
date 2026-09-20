<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="pdgal68-s"/><path class="jg4r9tbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:eventbrite-icon" /></template>
<style>
.jg4r9tbst {
  fill: var(--svg-color--fff, #fff);
  d: path("M117.475 82.729c19.297-4.288 38.595 3.574 49.315 18.582L81.502 120.61c2.859-18.345 16.676-33.592 35.973-37.88m49.792 70.756c-6.671 9.768-16.915 16.677-28.589 19.297c-19.297 4.288-38.832-3.573-49.553-18.82l85.527-19.298l13.818-3.097l26.682-5.956c-.238-5.717-.953-11.435-2.144-16.914c-10.72-45.98-57.653-74.806-104.586-64.086s-76.235 56.462-65.276 102.68s57.653 74.806 104.585 64.085c27.636-6.194 49.077-24.776 60.036-48.361z");
}

.pdgal68-s {
  cx: 128px;
  cy: 128px;
  r: 128px;
  fill: var(--svg-color--f05537, #f05537);
}

</style>
