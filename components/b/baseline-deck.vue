<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0ac6lg4f"/><path class="z6k6deb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-deck" /></template>
<style>
.n0ac6lg4f {
  fill: currentColor;
  d: path("M22 9L12 2L2 9h9v13h2V9z");
}

.z6k6deb5g {
  fill: currentColor;
  d: path("m4.14 12l-1.96.37l.82 4.37V22h2l.02-4H7v4h2v-6H4.9zm14.96 4H15v6h2v-4h1.98l.02 4h2v-5.26l.82-4.37l-1.96-.37z");
}

</style>
