<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pzugesi0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-add-20-regular" /></template>
<style>
.pzugesi0q {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M7 7H5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h4c.194 0 .382-.03.56-.081q.227.463.533.872A3 3 0 0 1 9 18H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2zm7.5 5a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5M15 2a3 3 0 0 1 3 3v5.257a5.5 5.5 0 0 0-1-.656V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v6c0 .488.175.935.466 1.282a5.5 5.5 0 0 0-.343 1.057A3 3 0 0 1 8 11V5a3 3 0 0 1 3-3z");
}

</style>
