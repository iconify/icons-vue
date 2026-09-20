<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="rhsa7ftfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:keycap-5" /></template>
<style>
.rhsa7ftfb {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.389 14.489c.744-.155 1.551-.31 2.326-.31c3.752 0 6.418 2.977 6.418 6.604c0 5.178-2.851 8.589-8.216 8.589c-2.201 0-6.821-1.427-6.821-4.155a2.13 2.13 0 0 1 2.108-2.107c1.24 0 2.729 1.984 4.806 1.984c2.17 0 3.288-2.109 3.288-4.062c0-1.86-1.055-3.131-2.977-3.131c-1.799 0-2.078 1.023-3.659 1.023c-1.209 0-1.829-.93-1.829-1.457c0-.403.062-.713.093-1.054l.774-6.544c.341-2.418.93-2.945 2.418-2.945h7.472c1.428 0 2.264.837 2.264 1.953c0 2.14-1.611 2.326-2.17 2.326h-5.829z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
