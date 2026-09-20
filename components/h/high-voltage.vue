<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rgmvpz51g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:high-voltage" /></template>
<style>
.rgmvpz51g {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M32.938 15.651A1 1 0 0 0 32 15H19.925L26.89 1.458A1 1 0 0 0 26 0a1 1 0 0 0-.653.243L18 6.588L3.347 19.243A1 1 0 0 0 4 21h12.075L9.11 34.542A1 1 0 0 0 10 36a1 1 0 0 0 .653-.243L18 29.412l14.653-12.655a1 1 0 0 0 .285-1.106");
}

</style>
