<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il5kb1b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cuboid-sharp-fill" /></template>
<style>
.il5kb1b2j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.2929 7.2929L7.2929 2.2929C7.4804 2.1054 7.7348 2 8 2L21 2C21.5523 2 22 2.4477 22 3L22 16C22 16.2652 21.8946 16.5196 21.7071 16.7071L16.7071 21.7071C16.5196 21.8946 16.2652 22 16 22L3 22C2.4477 22 2 21.5523 2 21L2 8C2 7.7348 2.1054 7.4804 2.2929 7.2929ZM5.4142 7L15.5858 7L18.5858 4L8.4142 4L5.4142 7Z");
}

</style>
