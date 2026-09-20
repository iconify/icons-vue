<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mas5i-bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:amp-error" /></template>
<style>
.mas5i-bla {
  fill: currentColor;
  d: path("M8.275 21L3 15.725v-7.45L8.275 3h7.45L21 8.275v7.45L15.725 21Zm2.075-1.5h.8L17 10.35h-4.2l.85-5.85h-.8l-5.9 9.15h4.2Z");
}

</style>
