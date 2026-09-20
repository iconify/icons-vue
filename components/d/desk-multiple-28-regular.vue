<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="hfpzo21fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-28-regular" /></template>
<style>
.hfpzo21fr {
  fill: currentColor;
  d: path("M20.75 6.5a2.75 2.75 0 0 1 2.75 2.75v14a.75.75 0 0 1-1.5 0V13h-9v8.25A2.75 2.75 0 0 1 10.25 24h-5.5A2.75 2.75 0 0 1 2 21.25v-12A2.75 2.75 0 0 1 4.75 6.5zM3.5 21.25c0 .69.56 1.25 1.25 1.25h5.5c.69 0 1.25-.56 1.25-1.25V13h-8zM20.752 4c2.9 0 5.25 2.35 5.25 5.25v11.5a.75.75 0 0 1-1.5 0V9.25a3.75 3.75 0 0 0-3.75-3.75H4.805A2.75 2.75 0 0 1 7.252 4zM9.25 15a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5zm-4.5-7c-.69 0-1.25.56-1.25 1.25v2.25H22V9.25C22 8.56 21.44 8 20.75 8z");
}

</style>
