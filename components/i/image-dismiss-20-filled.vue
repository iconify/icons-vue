<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="njfa0qboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-dismiss-20-filled" /></template>
<style>
.njfa0qboc {
  fill: currentColor;
  d: path("M9.65 11.148a.5.5 0 0 1 .7 0l5.384 5.3A3 3 0 0 1 14 17H6a3 3 0 0 1-1.734-.552zM14 3a3 3 0 0 1 3 3v8c0 .65-.207 1.251-.558 1.742l-5.39-5.307a1.5 1.5 0 0 0-2.105 0l-5.39 5.307A3 3 0 0 1 3 14v-3.602A5.5 5.5 0 0 0 10.398 3zM5.5 1a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m7 5.25a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5M7.354 3.646a.5.5 0 0 0-.708 0L5.5 4.793L4.354 3.646a.5.5 0 1 0-.708.708L4.793 5.5L3.646 6.646a.5.5 0 1 0 .708.708L5.5 6.207l1.146 1.147a.5.5 0 1 0 .708-.708L6.207 5.5l1.147-1.146a.5.5 0 0 0 0-.708");
}

</style>
