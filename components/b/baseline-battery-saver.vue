<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el6rbacjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-battery-saver" /></template>
<style>
.el6rbacjv {
  fill: currentColor;
  d: path("M16 4h-2V2h-4v2H8c-.55 0-1 .45-1 1v16c0 .55.45 1 1 1h8c.55 0 1-.45 1-1V5c0-.55-.45-1-1-1m-1 10h-2v2h-2v-2H9v-2h2v-2h2v2h2z");
}

</style>
