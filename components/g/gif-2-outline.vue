<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeio-9bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gif-2-outline" /></template>
<style>
.aeio-9bcx {
  fill: currentColor;
  d: path("M4 17q-.825 0-1.412-.587T2 15V9q0-.825.588-1.412T4 7h4q.825 0 1.413.588T10 9H4v6h4v-2H6v-2h4v4q0 .825-.587 1.413T8 17zm8 0V7h2v10zm4 0V7h7v2h-5v2h4v2h-4v4z");
}

</style>
