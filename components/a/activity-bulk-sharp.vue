<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvmucqbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:activity-bulk-sharp" /></template>
<style>
.jvmucqbjj {
  fill: currentColor;
  d: path("m5.279 11l2.772-8.316a1 1 0 0 1 1.898 0L15 17.838l2.051-6.154A1 1 0 0 1 18 11h3a1 1 0 0 1 0 2h-2.279l-2.772 8.316a1 1 0 0 1-1.898 0L9 6.162l-2.051 6.154A1 1 0 0 1 6 13H3a1 1 0 0 1 0-2Z");
}

</style>
