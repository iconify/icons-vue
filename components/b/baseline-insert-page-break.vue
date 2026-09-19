<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="featfqbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-insert-page-break" /></template>
<style>
.featfqbuw {
  fill: currentColor;
  d: path("M4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2v-3H4zM20 8l-6-6H6c-1.1 0-1.99.9-1.99 2v7H20zm-7 1V3.5L18.5 9zm-4 4h6v2H9zm8 0h6v2h-6zM1 13h6v2H1z");
}

</style>
