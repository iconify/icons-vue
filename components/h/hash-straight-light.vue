<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p776m8uxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hash-straight-light" /></template>
<style>
.p776m8uxt {
  fill: currentColor;
  d: path("M216 154h-50v-52h50a6 6 0 0 0 0-12h-50V40a6 6 0 0 0-12 0v50h-52V40a6 6 0 0 0-12 0v50H40a6 6 0 0 0 0 12h50v52H40a6 6 0 0 0 0 12h50v50a6 6 0 0 0 12 0v-50h52v50a6 6 0 0 0 12 0v-50h50a6 6 0 0 0 0-12m-114 0v-52h52v52Z");
}

</style>
