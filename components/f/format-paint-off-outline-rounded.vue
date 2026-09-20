<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9324hb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paint-off-outline-rounded" /></template>
<style>
.e9324hb8c {
  fill: currentColor;
  d: path("M12.663 6.818q-.144-.143-.144-.356V5H7.811l-.888-.889q.17-.065.347-.088Q7.448 4 7.635 4h10.557q.349 0 .578.23t.23.578v8.384q0 .612-.398 1.054t-1.03.514l-.972-.972h.746q.27 0 .462-.173t.192-.423v-1.73h-3.727l-1-1H18V5h-1.634v3.212q0 .213-.144.356q-.143.144-.357.144q-.213 0-.356-.144t-.143-.356V5h-1.847v1.462q0 .213-.143.356t-.357.144t-.356-.144M10.962 21q-.421 0-.711-.29q-.29-.289-.29-.71v-5.212H6.635q-.69 0-1.162-.462Q5 13.863 5 13.192V6.427L3.094 4.521q-.146-.146-.153-.347t.159-.366t.357-.166t.356.166l16.38 16.384q.145.146.155.344t-.156.364q-.165.165-.356.165q-.192 0-.357-.165l-5.46-5.454V20q0 .421-.29.71q-.288.29-.71.29zm-4.327-7.212h5.727l-2.328-2.327H6v1.731q0 .25.183.424q.183.173.452.173M6 10.462h3.035L6 7.427zm6.362 3.327H6zm4.238 0H18z");
}

</style>
