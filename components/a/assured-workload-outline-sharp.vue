<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q625l365h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:assured-workload-outline-sharp" /></template>
<style>
.q625l365h {
  fill: currentColor;
  d: path("M5 17v-7h2v7zm6 0v-7h2v7zM2 8V6l10-5l10 5v2zm4.475-2h11.05L12 3.25zM2 21v-2h12.05q.05.525.125 1.013T14.4 21zm15-7.75V10h2v2.25zM20 24q-1.725-.425-2.863-1.987T16 18.55V16l4-2l4 2v2.55q0 1.9-1.137 3.463T20 24m-.725-3l3.475-3.45l-1.05-1.05l-2.425 2.375l-.975-.975l-1.05 1.075zM6.475 6h11.05z");
}

</style>
