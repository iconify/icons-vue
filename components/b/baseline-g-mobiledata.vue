<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl0e5bb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-g-mobiledata" /></template>
<style>
.nl0e5bb7y {
  fill: currentColor;
  d: path("M12 11v2h2v2H9V9h7c0-1.1-.9-2-2-2H9c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h5c1.1 0 2-.9 2-2v-4z");
}

</style>
