<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c526wmb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:high-voltage" /></template>
<style>
.c526wmb6z {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m44.5 2l-9 2.5L29.4 2l-9.9 34.4h10.4L20.8 62l22.4-34.4H29.7z");
}

</style>
