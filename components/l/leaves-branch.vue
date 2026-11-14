<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thrto8bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaves-branch" /></template>
<style>
.thrto8bdd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.25Q9.25 1.25 9.25 5q0 3.198 2 3.669v2.143Q9.206 8.444 5.539 8.251q-.073-.004-.146.007q-.074.01-.143.035q-.07.025-.133.062q-.064.038-.119.088t-.099.108t-.076.126t-.05.138q-.018.072-.022.146q-.009.168.055.325q1.797 4.362 6.444 4.903v4.123q-2.044-2.368-5.711-2.561q-.073-.004-.146.007q-.074.01-.143.035q-.07.025-.133.062q-.064.038-.119.088t-.099.108q-.044.059-.076.126t-.05.138t-.022.146q-.009.168.055.325q1.931 4.687 7.152 4.963h.004L12.75 21v-3.061q4.647-.541 6.444-4.903q.064-.157.055-.325q-.008-.149-.072-.284t-.175-.234q-.111-.1-.252-.15q-.14-.05-.289-.042q-3.667.193-5.711 2.561V8.669q2-.471 2-3.669q0-3.75-2.75-3.75");
}

</style>
