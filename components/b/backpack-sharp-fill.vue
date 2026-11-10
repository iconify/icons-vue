<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ly6bmhb5u"/><path clip-rule="evenodd" class="e2vh-q-gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:backpack-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e2vh-q-gh {
  fill-rule: evenodd;
  d: path("M12 1C14.17 1 15.939 2.845 16 5H20C20.552 5 21 5.448 21 6V14H3V6C3 5.448 3.448 5 4 5H8C8.061 2.845 9.83 1 12 1ZM9 9V11H15V9H9ZM12 3C10.938 3 10.064 3.955 9.998 5H14.002C13.936 3.955 13.062 3 12 3Z");
}

.ly6bmhb5u {
  d: path("M7 16V19H9V16H21V22C21 22.552 20.552 23 20 23H4C3.448 23 3 22.552 3 22V16H7Z");
}

</style>
