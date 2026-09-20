<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vhpv4p0dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:conference-room-20-filled" /></template>
<style>
.vhpv4p0dp {
  fill: currentColor;
  d: path("M9.186 2.113a.5.5 0 0 1 .419-.1l7 1.499a.5.5 0 0 1 .394.489v12a.5.5 0 0 1-.395.489l-7 1.5A.5.5 0 0 1 9 17.503v-15a.5.5 0 0 1 .186-.389m3.316 7.888a.75.75 0 1 0-1.5 0a.75.75 0 0 0 1.5 0m-4.5-6.998H3.5a.5.5 0 0 0-.5.5v12.995a.5.5 0 0 0 .5.5h4.502z");
}

</style>
