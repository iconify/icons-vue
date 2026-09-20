<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egud3sbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-go-rounded" /></template>
<style>
.egud3sbsc {
  fill: currentColor;
  d: path("M19.367 17.5H13q-.213 0-.357-.143T12.5 17t.143-.357T13 16.5h6.367l-1.727-1.727q-.14-.14-.15-.341t.156-.367q.16-.16.354-.16t.354.16l2.369 2.37q.243.242.243.565t-.243.566l-2.37 2.369q-.145.146-.343.153q-.198.006-.364-.16q-.16-.165-.162-.353q-.003-.189.162-.354zM5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.636q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985h4.63q.672 0 1.144.472T20 5.616v5.596q0 .213-.143.356t-.357.144t-.357-.144t-.143-.356V5.616q0-.231-.192-.424T18.384 5H16v1.423q0 .348-.23.578t-.578.23H8.808q-.348 0-.578-.23T8 6.423V5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192H10q.214 0 .357.143t.143.357t-.143.357T10 20zm6.962-14.999q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
