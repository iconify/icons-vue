<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q87z5sbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lda-outline-sharp" /></template>
<style>
.q87z5sbju {
  fill: currentColor;
  d: path("M11 22v-3.425L5 16.05V11h6V8H8V2h8v6h-3v3h6v5.05l-6 2.525V22zM10 6h4V4h-4zm1 10.4V13H7v1.725zm2 0l4-1.675V13h-4zM10 6V4z");
}

</style>
