<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fvo_st2lt"/><path class="rrla16g1f"/><path class="ti19ytvcr"/><path class="r72pl9b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-sudan" /></template>
<style>
.fvo_st2lt {
  fill: var(--svg-color--d21034, #d21034);
  d: path("M32 5H4a4 4 0 0 0-4 4v4.5h36V9a4 4 0 0 0-4-4");
}

.r72pl9b-r {
  fill: var(--svg-color--007229, #007229);
  d: path("M1.351 6.004A4 4 0 0 0 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18z");
}

.rrla16g1f {
  fill: var(--svg-color--141414, #141414);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4.5H0z");
}

.ti19ytvcr {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13.5h36v9H0z");
}

</style>
