<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzekrdboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:landscape-sharp" /></template>
<style>
.vzekrdboh {
  fill: currentColor;
  d: path("m1 18l6-8l4.5 6h2.525l-3.775-5L14 6l9 12z");
}

</style>
