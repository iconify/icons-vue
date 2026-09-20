<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0d_6gbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gitlab" /></template>
<style>
.l0d_6gbnl {
  fill: currentColor;
  d: path("M11.5 20.85L4.525 15.6q-1.275-.95-1.7-2.5t.15-3.05l2.55-6.625q.075-.2.25-.312T6.15 3t.388.113t.262.362L8.525 8.75h6.95L17.2 3.475q.075-.25.263-.363T17.85 3t.375.113t.25.312L21 10.05q.575 1.5.15 3.05t-1.7 2.5l-7 5.25q-.2.15-.475.15t-.475-.15");
}

</style>
