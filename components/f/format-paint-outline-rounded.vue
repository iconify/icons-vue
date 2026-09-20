<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvqxsky0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paint-outline-rounded" /></template>
<style>
.lvqxsky0z {
  fill: currentColor;
  d: path("M10.962 21q-.421 0-.711-.29q-.29-.289-.29-.71v-5.212H6.635q-.69 0-1.162-.462Q5 13.863 5 13.192V6.596q0-1.073.771-1.834T7.635 4h10.557q.349 0 .578.23t.23.578v8.384q0 .672-.482 1.134t-1.172.463H14.02V20q0 .421-.29.71q-.288.29-.71.29zM6 10.462h12V5h-1.634v3.212q0 .213-.144.356q-.143.144-.357.144q-.213 0-.356-.144t-.143-.356V5h-1.847v1.462q0 .213-.143.356t-.357.144t-.356-.144t-.144-.356V5H7.635q-.69 0-1.163.453Q6 5.906 6 6.596zm.635 3.327h10.711q.27 0 .462-.173q.192-.174.192-.424v-1.73H6v1.73q0 .25.183.424q.183.173.452.173m-.635 0v-2.327z");
}

</style>
