<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsqmktqhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paint-off-outline" /></template>
<style>
.wsqmktqhq {
  fill: currentColor;
  d: path("M19 4v9.192q0 .612-.398 1.054t-1.03.513l-.972-.97h.746q.27 0 .462-.174q.192-.173.192-.423v-1.73h-3.727l-1-1H18V5h-1.634v3.712h-1V5h-1.847v1.962h-1V5H7.811l-.888-.889q.17-.065.347-.088Q7.448 4 7.635 4zm.833 17.26l-5.814-5.814V20q0 .421-.29.71q-.288.29-.71.29h-2.058q-.42 0-.71-.29q-.29-.289-.29-.71v-5.212H6.635q-.69 0-1.162-.462Q5 13.863 5 13.192V6.427l-2.26-2.26l.714-.713l17.092 17.092zM6.635 13.787h5.727l-2.328-2.327H6v1.731q0 .25.183.424q.183.173.452.173M6 10.462h3.035L6 7.427zm6.362 3.327H6zm4.238 0H18z");
}

</style>
