<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u132lbbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heat-pump-balance-outline-sharp" /></template>
<style>
.u132lbbpg {
  fill: currentColor;
  d: path("M4.5 7.754h1v8.769h3v-8.77h5v8.77h3v-9.77h4.887L19.712 5.08l.688-.713l2.889 2.888l-2.889 2.863l-.688-.713l1.694-1.65H17.5v9.769h-5v-8.77h-3v8.77h-5zM2 20.6v-8.461h20V20.6zm1-1h18v-6.462H3zm18-6.461H3z");
}

</style>
