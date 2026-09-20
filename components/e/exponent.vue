<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":240};
const content = `<path class="hyr9zlbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:exponent" /></template>
<style>
.hyr9zlbtw {
  d: path("M94.104-.001L0 217.125l42.193 22.519L128 55.703l85.57 183.941L256 217.125L161.896-.001H94.104z");
  fill: var(--svg-color--023c69, #023C69);
}

</style>
