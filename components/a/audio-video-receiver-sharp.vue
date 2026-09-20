<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kai0cwb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:audio-video-receiver-sharp" /></template>
<style>
.kai0cwb_p {
  fill: currentColor;
  d: path("M2 17V5h20v12h-2v2h-2v-2H6v2H4v-2zm15.913-4.587q.587-.588.587-1.413t-.587-1.412T16.5 9t-1.412.588T14.5 11t.588 1.413T16.5 13t1.413-.587M6 13h7V9H6z");
}

</style>
