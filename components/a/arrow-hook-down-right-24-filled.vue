<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbcjvkb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-down-right-24-filled" /></template>
<style>
.sbcjvkb0f {
  fill: currentColor;
  d: path("M10.5 6H16a1 1 0 1 0 0-2h-5.5a6.5 6.5 0 0 0 0 13h5.14l-1.933 1.933a1 1 0 0 0 1.414 1.414l3.53-3.529a1 1 0 0 0 .21-.308a1 1 0 0 0-.18-1.243l-.028-.029l-3.531-3.53a1 1 0 0 0-1.415 1.413L15.586 15H10.5a4.5 4.5 0 1 1 0-9");
}

</style>
