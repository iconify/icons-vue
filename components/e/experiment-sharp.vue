<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5bsfnbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:experiment-sharp" /></template>
<style>
.f5bsfnbbd {
  fill: currentColor;
  d: path("M5 21q-1.275 0-1.812-1.137t.262-2.113L9 11V5H7V3h10v2h-2v6l5.55 6.75q.8.975.263 2.113T19 21zm2-3h10l-3.4-4h-3.2z");
}

</style>
