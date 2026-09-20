<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7eo1mbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gavel-outline-rounded" /></template>
<style>
.i7eo1mbdf {
  fill: currentColor;
  d: path("M5 19h10q.425 0 .713.288T16 20t-.288.713T15 21H5q-.425 0-.712-.288T4 20t.288-.712T5 19m3.225-4.275L5.4 11.9q-.575-.575-.587-1.412t.562-1.413L6.1 8.35L11.8 14l-.725.725q-.575.575-1.425.575t-1.425-.575M16 9.8l-5.65-5.7l.725-.725q.575-.575 1.413-.562T13.9 3.4l2.825 2.825q.575.575.575 1.425t-.575 1.425zm3.9 9.5L7.55 6.95l1.4-1.4L21.3 17.9q.275.275.275.7t-.275.7t-.7.275t-.7-.275");
}

</style>
