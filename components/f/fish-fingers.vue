<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cugrtnb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fish-fingers" /></template>
<style>
.cugrtnb-d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.765 2.552q1.064-.226 1.976.367q.912.592 1.138 1.656l2.339 11.004q.226 1.064-.366 1.975q-.592.912-1.656 1.139t-1.976-.367q-.912-.592-1.138-1.656L14.743 5.666q-.226-1.064.366-1.975q.592-.912 1.656-1.139M12.382 4.27q-.911-.592-1.975-.366q-1.064.227-1.656 1.139q-.592.911-.366 1.975l2.339 11.004q.227 1.064 1.139 1.656q.911.592 1.975.366q1.064-.227 1.656-1.139q.592-.911.366-1.975L13.521 5.926q-.227-1.064-1.139-1.656m-8.333.985q1.064-.226 1.976.367q.912.592 1.138 1.656l2.339 11.004q.226 1.064-.366 1.975q-.592.912-1.656 1.139t-1.976-.367q-.912-.592-1.138-1.656L2.027 8.369q-.226-1.064.366-1.975q.592-.912 1.656-1.139");
}

</style>
