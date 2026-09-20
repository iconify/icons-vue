<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a6c63ccrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lockers-light" /></template>
<style>
.a6c63ccrg {
  fill: currentColor;
  d: path("M190 72a6 6 0 0 1-6 6h-24a6 6 0 0 1 0-12h24a6 6 0 0 1 6 6m-6 26h-24a6 6 0 0 0 0 12h24a6 6 0 0 0 0-12M72 78h24a6 6 0 0 0 0-12H72a6 6 0 0 0 0 12m24 20H72a6 6 0 0 0 0 12h24a6 6 0 0 0 0-12m126-50v176a6 6 0 0 1-12 0v-18h-76v18a6 6 0 0 1-12 0v-18H46v18a6 6 0 0 1-12 0V48a14 14 0 0 1 14-14h160a14 14 0 0 1 14 14M122 194V46H48a2 2 0 0 0-2 2v146Zm12 0h76V48a2 2 0 0 0-2-2h-74Z");
}

</style>
