<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvp_9qbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:audio-video-receiver-outline-sharp" /></template>
<style>
.mvp_9qbvr {
  fill: currentColor;
  d: path("M4 15h16V7H4zm-2 2V5h20v12h-2v2h-2v-2H6v2H4v-2zm2-2V7zm13.913-2.588q.587-.587.587-1.412t-.587-1.412T16.5 9t-1.412.588T14.5 11t.588 1.413T16.5 13t1.413-.587M6 13h7V9H6z");
}

</style>
