<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5lzb_b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-export-sharp" /></template>
<style>
.g5lzb_b5a {
  fill: currentColor;
  d: path("m16.9 21.789l-.688-.689l3.575-3.6H16.5v-1h5v5h-1v-3.292zM7.044 20q-1.032 0-1.928-.504q-.897-.504-1.42-1.38q-.523-.877-.523-1.885t.523-1.885l1.09-1.846h3.906l4.37 7.5zm-1.678-8.5l3.311-5.596q.523-.877 1.41-1.39T12 4t1.904.514t1.4 1.39l1.365 2.302l-1.934 3.294zm8.982 2.664l2.9-4.983l2 3.377q-1.344-.175-2.624.24q-1.28.416-2.276 1.366");
}

</style>
