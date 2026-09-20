<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9gh_-bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:expand-all-outline" /></template>
<style>
.h9gh_-bqw {
  fill: currentColor;
  d: path("M12 21.308L6.692 16l.714-.713L12 19.842l4.594-4.555l.714.713zm-4.588-12.6L6.692 8L12 2.692L17.308 8l-.72.708L12 4.158z");
}

</style>
