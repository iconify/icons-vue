<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vhmyyqqmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-top-left-bottom-right-28-filled" /></template>
<style>
.vhmyyqqmn {
  fill: currentColor;
  d: path("M12.5 3.5a1 1 0 1 1 0 2H6.914L22.5 21.086V15.5a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1h-8a1 1 0 1 1 0-2h5.586L5.5 6.914V12.5a1 1 0 1 1-2 0v-8a1 1 0 0 1 1-1z");
}

</style>
