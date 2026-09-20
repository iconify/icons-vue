<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_u1a3bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ice-skating-sharp" /></template>
<style>
.g_u1a3bmu {
  fill: currentColor;
  d: path("M2.5 21.5v-1h4v-3h-3v-14h7.308v2.616H8.116v.769h2.761v1.23H8.116v.77h3.034q.312.575.83.975t1.168.6l5.16 1.428V17.5H15.5v3H18q1.346 0 2.356-.836q1.01-.837 1.144-2.164h1q-.134 1.729-1.443 2.865Q19.748 21.5 18 21.5zm5-1h7v-3h-7z");
}

</style>
