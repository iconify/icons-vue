<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-k1hmi9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bluetooth-connected-outline" /></template>
<style>
.z-k1hmi9q {
  fill: currentColor;
  d: path("M11 22v-7.6L6.4 19L5 17.6l5.6-5.6L5 6.4L6.4 5L11 9.6V2h1l5.7 5.7l-4.3 4.3l4.3 4.3L12 22zm2-12.4l1.9-1.9L13 5.85zm0 8.55l1.9-1.85l-1.9-1.9zm-9.062-5.087Q3.5 12.625 3.5 12t.438-1.062T5 10.5t1.063.438T6.5 12t-.437 1.063T5 13.5t-1.062-.437m14 0Q17.5 12.625 17.5 12t.438-1.062T19 10.5t1.063.438T20.5 12t-.437 1.063T19 13.5t-1.062-.437");
}

</style>
