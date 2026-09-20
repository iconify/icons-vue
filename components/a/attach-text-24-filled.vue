<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnzi4pmll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:attach-text-24-filled" /></template>
<style>
.mnzi4pmll {
  fill: currentColor;
  d: path("M7 3a5 5 0 0 1 4.995 4.783L12 8v11a3 3 0 0 1-5.995.176L6 19V9a1 1 0 0 1 1.993-.117L8 9v10a1 1 0 0 0 1.993.117L10 19V8a3 3 0 0 0-5.995-.176L4 8v9a1 1 0 0 1-1.993.117L2 17V8a5 5 0 0 1 5-5m8 14h2a1 1 0 0 1 .117 1.993L17 19h-2a1 1 0 0 1-.117-1.993zh2zm0-4h5.5a1 1 0 0 1 .117 1.993L20.5 15H15a1 1 0 0 1-.117-1.993zh5.5zm0-4h5.5a1 1 0 0 1 .117 1.993L20.5 11H15a1 1 0 0 1-.117-1.993zh5.5zm0-4h5.5a1 1 0 0 1 .117 1.993L20.5 7H15a1 1 0 0 1-.117-1.993zh5.5z");
}

</style>
