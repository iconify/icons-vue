<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyy65d0hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-bag-sharp" /></template>
<style>
.fyy65d0hz {
  fill: currentColor;
  d: path("M9 14h1v1h1.5v-1h1v1H14v-1h1V8h-1.5V6h-3v2H9zm2.5-6V7h1v1zM5 21V3h14v18l-7-3z");
}

</style>
