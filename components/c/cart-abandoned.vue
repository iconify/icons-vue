<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fpkqjru6p"/><path class="d6s0bwqti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-abandoned" /></template>
<style>
.d6s0bwqti {
  d: path("M2.5 2.5h2L6.75 11m0 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m7.383-.58q-.042-.102-.099-.196q-.058-.095-.128-.18t-.152-.158t-.173-.135t-.192-.108t-.205-.079t-.215-.048T12.75 13q-.074 0-.147.007t-.146.022q-.072.014-.142.036q-.071.021-.139.049t-.133.063t-.126.076q-.062.041-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126t-.063.133t-.049.139q-.022.07-.036.142q-.015.073-.022.146t-.007.147t.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126t.087.119t.099.109t.109.099q.057.046.119.087t.126.076t.133.063t.139.049q.07.022.142.036q.073.015.146.022t.147.007q.256 0 .498-.085M16 16l5.5 5.5m0-5.5L16 21.5");
}

.fpkqjru6p {
  d: path("M7.283 4.5H16.3a1.75 1.75 0 0 1 1.705 2.144l-.692 3A1.75 1.75 0 0 1 15.608 11H8.091a1.75 1.75 0 0 1-1.69-1.295l-.807-3A1.75 1.75 0 0 1 7.283 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
