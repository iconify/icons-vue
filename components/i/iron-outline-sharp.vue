<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swb-7yaqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:iron-outline-sharp" /></template>
<style>
.swb-7yaqg {
  fill: currentColor;
  d: path("M3 17v-2.077q0-1.364.992-2.336t2.412-.971h8.962V9H9.269v1.5h-1V8h8.097v6.462H18V7h3v1h-2v7.462h-2.634V17zm1-1h11.366v-3.384H6.404q-.992 0-1.698.677Q4 13.971 4 14.923zm11.366 0v-3.384z");
}

</style>
