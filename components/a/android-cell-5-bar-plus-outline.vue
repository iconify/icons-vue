<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlsoegprc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-cell-5-bar-plus-outline" /></template>
<style>
.qlsoegprc {
  fill: currentColor;
  d: path("M2 19v-4.712h1.692V19zm4.577 0v-6.577h1.692V19zm4.577 0V9.654h1.692V19zM22 12.289q-.375-.245-.801-.392t-.891-.205V5H22zm-6.27-4.5h1.693v4.325q-.517.246-.958.613q-.442.367-.734.852zM19.039 19v-2h-2v-1h2v-2h1v2h2v1h-2v2z");
}

</style>
