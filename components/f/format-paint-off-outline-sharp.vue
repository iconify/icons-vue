<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui2t3sbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paint-off-outline-sharp" /></template>
<style>
.ui2t3sbab {
  fill: currentColor;
  d: path("M19 4v10.76h-1.429l-.971-.972H18v-2.327h-3.727l-1-1H18V5h-1.634v3.712h-1V5h-1.847v1.962h-1V5H7.811l-.888-.889q.17-.065.345-.088Q7.444 4 7.635 4zm.833 17.26l-5.814-5.814V21H9.962v-6.212H5V6.427l-2.26-2.26l.714-.713l17.092 17.092zM6 13.787h6.362l-2.328-2.327H6zm0-3.327h3.035L6 7.427zm6.362 3.327H6zm4.238 0H18z");
}

</style>
