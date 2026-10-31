<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o7yp9nbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-32-regular" /></template>
<style>
.o7yp9nbtd {
  fill: currentColor;
  d: path("M25.5 19a4.5 4.5 0 0 1 4.5 4.5v2a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 25.5v-2a4.5 4.5 0 0 1 3.886-4.458l-.322 1.395a2.5 2.5 0 0 0-.055.767A2.5 2.5 0 0 0 4 23.5v2A2.5 2.5 0 0 0 6.5 28h19a2.5 2.5 0 0 0 2.5-2.5v-2a2.5 2.5 0 0 0-2.5-2.5h-8.974q.076-.067.148-.138L18.536 19zm-3-17A4.5 4.5 0 0 1 27 6.5v.05a4.5 4.5 0 0 1-1.318 3.182l-10.07 10.07a3 3 0 0 1-1.446.802l-5.941 1.37a1 1 0 0 1-1.2-1.199l1.371-5.941a3 3 0 0 1 .802-1.446l10.07-10.07A4.5 4.5 0 0 1 22.45 2zm-.05 2c-.663 0-1.3.264-1.768.732l-10.07 10.07a1 1 0 0 0-.266.482l-1.012 4.381l4.382-1.01a1 1 0 0 0 .482-.267l10.07-10.07A2.5 2.5 0 0 0 25 6.55V6.5A2.5 2.5 0 0 0 22.5 4z");
}

</style>
