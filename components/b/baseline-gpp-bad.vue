<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvc97oxqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-gpp-bad" /></template>
<style>
.kvc97oxqo {
  fill: currentColor;
  d: path("M12 2L4 5v6.09c0 5.05 3.41 9.76 8 10.91c4.59-1.15 8-5.86 8-10.91V5zm3.5 12.09l-1.41 1.41L12 13.42L9.91 15.5L8.5 14.09L10.59 12L8.5 9.91L9.91 8.5L12 10.59l2.09-2.09l1.41 1.41L13.42 12z");
}

</style>
