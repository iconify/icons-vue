<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzseqr7fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-chromebook-outline" /></template>
<style>
.vzseqr7fo {
  fill: currentColor;
  d: path("M1 18.308v-1h2V4.538h18v12.77h2v1zm9-1h4v-.77h-4zm-6-1.77h16v-10H4zm8-5");
}

</style>
