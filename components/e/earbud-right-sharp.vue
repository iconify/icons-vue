<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7k103kav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:earbud-right-sharp" /></template>
<style>
.z7k103kav {
  fill: currentColor;
  d: path("M12 22V4h9v8h-3v10zm-3-8q-2.5 0-4.25-1.75T3 8t1.75-4.25T9 2h1v12z");
}

</style>
