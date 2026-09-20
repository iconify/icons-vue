<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t6up7bbuc"/><path class="x6l14xyck"/><path class="xpy8sjkzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-st-martin" /></template>
<style>
.t6up7bbuc {
  fill: var(--svg-color--ed2939, #ed2939);
  d: path("M36 27a4 4 0 0 1-4 4h-8V5h8a4 4 0 0 1 4 4z");
}

.x6l14xyck {
  fill: var(--svg-color--002495, #002495);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

.xpy8sjkzl {
  fill: var(--svg-color--eee, #eee);
  d: path("M12 5h12v26H12z");
}

</style>
