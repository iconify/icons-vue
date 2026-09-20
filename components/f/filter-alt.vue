<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrz_m-l3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-alt" /></template>
<style>
.lrz_m-l3j {
  fill: currentColor;
  d: path("M11.77 19q-.33 0-.55-.22t-.22-.55v-5.576L5.604 5.83q-.202-.27-.055-.55t.47-.28h11.962q.323 0 .47.28q.147.282-.055.55L13 12.655v5.577q0 .328-.22.549t-.55.22z");
}

</style>
