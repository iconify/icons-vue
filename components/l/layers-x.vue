<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua_ynlb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-x" /></template>
<style>
.ua_ynlb9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.4382 2.1011L21.4382 6.4886C22.1873 6.8538 22.1873 7.9212 21.4382 8.2864L12.4382 12.6739C12.1616 12.8087 11.8384 12.8087 11.5618 12.6739L2.5618 8.2864C1.8127 7.9212 1.8127 6.8538 2.5618 6.4886L11.5618 2.1011C11.8384 1.9663 12.1616 1.9663 12.4382 2.1011ZM2 12.625L11.5618 17.2864C11.7001 17.3538 11.85 17.3875 12 17.3875M2 17.2375L11.5618 21.8989C11.7001 21.9663 11.85 22 12 22M16 16L22 22M22 16L16 22");
}

</style>
