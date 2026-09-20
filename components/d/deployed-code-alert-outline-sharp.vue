<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6oo1wb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-alert-outline-sharp" /></template>
<style>
.y6oo1wb8w {
  fill: currentColor;
  d: path("m12 11.427l6.425-3.713L12 4L5.575 7.714zm-8 5.121v-9.1l8-4.594l8 4.598v4.394h-1V8.523l-7.025 4.05L5 8.523v7.427l6.736 3.898v1.127zm14 4.779q.2 0 .33-.13t.132-.332t-.131-.33t-.331-.131t-.33.13q-.132.132-.132.332t.131.33t.331.131m-.385-1.923h.77v-3.231h-.77zm-2.45 2.181Q14 20.422 14 18.75t1.165-2.835T18 14.75t2.836 1.165T22 18.75t-1.164 2.836T18 22.75t-2.835-1.164m-3.428-9.65");
}

</style>
