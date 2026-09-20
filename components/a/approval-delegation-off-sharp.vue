<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar7qpzqic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:approval-delegation-off-sharp" /></template>
<style>
.ar7qpzqic {
  fill: currentColor;
  d: path("M13.925 11.05L9.675 6.8L11.1 5.4l2.825 2.825l5.675-5.65l1.4 1.4zm8.025 10.9l-1.4 1.4L.65 3.45l1.4-1.4zM8 20.025V11h1.6q.175 0 .35.038t.35.087l1.275.45L16 16h-1.825q-.125 0-.187-.012t-.163-.063l-1.6-.625l-.325.975l1.925.675q.05.025.15.038t.175.012H17l3.075 3.075L15.025 22zM2 22V11h4v11z");
}

</style>
