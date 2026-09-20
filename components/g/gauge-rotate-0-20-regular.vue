<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rj7h1uncu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-0-20-regular" /></template>
<style>
.rj7h1uncu {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 1a7 7 0 1 0 0 14a7 7 0 0 0 0-14m-.608 1.416c.197-.559 1.02-.559 1.216 0l.033.129c.258 1.679.534 3.356.76 5.04c.056.414.099.766.099.914a1.5 1.5 0 1 1-3 0c0-.148.043-.5.099-.914c.176-1.31.552-3.72.76-5.04z");
}

</style>
