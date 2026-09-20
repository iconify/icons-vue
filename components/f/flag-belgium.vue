<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="oh2-6ea0q"/><path class="f4cj0ct6j"/><path class="jjq608bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-belgium" /></template>
<style>
.f4cj0ct6j {
  fill: var(--svg-color--fdda24, #fdda24);
  d: path("M13 5h10v26H13z");
}

.jjq608bfj {
  fill: var(--svg-color--ef3340, #ef3340);
  d: path("M29 5h-6v26h6a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.oh2-6ea0q {
  fill: var(--svg-color--141414, #141414);
  d: path("M7 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h6V5z");
}

</style>
