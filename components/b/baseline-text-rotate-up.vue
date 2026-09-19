<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veiga2zyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-text-rotate-up" /></template>
<style>
.veiga2zyu {
  fill: currentColor;
  d: path("M3 12v1.5l11 4.75v-2.1l-2.2-.9v-5l2.2-.9v-2.1zm7 2.62l-5.02-1.87L10 10.88zm8-10.37l-3 3h2v12.5h2V7.25h2z");
}

</style>
