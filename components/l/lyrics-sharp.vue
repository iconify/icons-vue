<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziex-wbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lyrics-sharp" /></template>
<style>
.ziex-wbvx {
  fill: currentColor;
  d: path("M7.077 13.5h3v-1h-3zm11.54-2q-1.04 0-1.77-.728t-.731-1.77t.729-1.771t1.77-.731q.487 0 .824.137t.677.461V1.5h3v1h-2V9q0 1.042-.729 1.77q-.729.73-1.77.73m-11.54-1h6v-1h-6zm0-3h6v-1h-6zm-3.5 12.077V3h13v1.867q-1.183.581-1.88 1.694T14 9t.697 2.44t1.88 1.693V17H6.154z");
}

</style>
