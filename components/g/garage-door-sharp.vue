<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_52o7-kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-door-sharp" /></template>
<style>
.d_52o7-kj {
  fill: currentColor;
  d: path("M5 19.02V9.634H3.437L12 3.077l8.539 6.558H19v9.384zm3.327-.886h7.346V16.25H8.327zm0-2.769h7.346v-1.884H8.327zm0-2.769h7.346v-1.885H8.327zm3.683-4.615q.3 0 .51-.21t.21-.52t-.21-.521t-.52-.21q-.29 0-.51.21q-.22.209-.22.52t.22.52t.52.21");
}

</style>
