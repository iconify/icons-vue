<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om5lwy3ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-left-fill" /></template>
<style>
.om5lwy3ly {
  fill: currentColor;
  d: path("M21 10v4a2 2 0 0 1-2 2h-6v3c.001.203-.047.402-.14.582c-.371.712-1.242.835-1.932.549a2 2 0 0 1-.635-.424l-6-6a2.414 2.414 0 0 1 0-3.414l6-6c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v3h6a2 2 0 0 1 2 2");
}

</style>
