<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mq8yb_3kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:espejo" /></template>
<style>
.mq8yb_3kg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.97 25.822l28.946 16.655M8.969 21.79l30.06 17.297M8.97 18.631l30.06 17.296M17.698 4.501L39.03 16.776M12.626 4.5h22.75a3.64 3.64 0 0 1 3.655 3.627v31.73a3.64 3.64 0 0 1-3.639 3.643H12.626a3.64 3.64 0 0 1-3.655-3.627V8.143A3.64 3.64 0 0 1 12.61 4.5z");
}

</style>
