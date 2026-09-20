<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb7503vqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-note" /></template>
<style>
.nb7503vqy {
  fill: currentColor;
  d: path("M5 14v-1h7v1zm0-4V9h11v1zm0-4V5h11v1zm8.23 13v-2.21l5.334-5.307q.148-.13.305-.19t.315-.062q.172 0 .338.064q.166.065.301.194l.925.944q.123.148.188.308q.064.159.064.319t-.052.322t-.2.31L15.44 19zm5.96-4.985l.925-.956l-.924-.943l-.95.95z");
}

</style>
