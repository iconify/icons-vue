<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="v1uudqb1q"/><path class="n97i-i-mr"/><path class="u8rrg1krc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-congo-brazzaville" /></template>
<style>
.n97i-i-mr {
  fill: var(--svg-color--fbde4a, #fbde4a);
  d: path("M32 5h-6L1.172 29.828A4 4 0 0 0 4 31h6L34.828 6.172A4 4 0 0 0 32 5");
}

.u8rrg1krc {
  fill: var(--svg-color--dc241f, #dc241f);
  d: path("M10 31h22a4 4 0 0 0 4-4V9a4 4 0 0 0-1.172-2.828z");
}

.v1uudqb1q {
  fill: var(--svg-color--009543, #009543);
  d: path("M4 5a4 4 0 0 0-4 4v18c0 1.104.448 2.104 1.172 2.828L26 5z");
}

</style>
