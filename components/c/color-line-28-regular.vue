<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zlt6uof4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-28-regular" /></template>
<style>
.zlt6uof4o {
  fill: currentColor;
  d: path("M22.251 17a3.75 3.75 0 0 1 3.75 3.75v1.5a3.75 3.75 0 0 1-3.75 3.75H5.754a3.75 3.75 0 0 1-3.75-3.75v-1.5a3.75 3.75 0 0 1 3.227-3.714l-.187.825c-.057.253-.055.51-.002.755a2.25 2.25 0 0 0-1.538 2.134v1.5a2.25 2.25 0 0 0 2.25 2.25H22.25a2.25 2.25 0 0 0 2.25-2.25v-1.5a2.25 2.25 0 0 0-2.25-2.25h-9.272c.336-.175.647-.4.919-.67l.829-.83zM19.246 2a3.76 3.76 0 0 1 3.756 3.755c0 .994-.395 1.95-1.099 2.654l-8.713 8.713c-.366.367-.83.622-1.335.737l-4.939 1.122a.75.75 0 0 1-.897-.897l1.124-4.937a2.75 2.75 0 0 1 .736-1.335l8.714-8.713A3.76 3.76 0 0 1 19.246 2m0 1.5c-.597 0-1.171.238-1.593.66L8.94 12.871a1.25 1.25 0 0 0-.335.607l-.86 3.775l3.778-.858c.23-.052.44-.168.607-.335l8.713-8.712a2.26 2.26 0 0 0 .659-1.594A2.26 2.26 0 0 0 19.246 3.5");
}

</style>
