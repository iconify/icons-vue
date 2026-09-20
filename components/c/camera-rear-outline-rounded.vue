<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thcqspufj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-rear-outline-rounded" /></template>
<style>
.thcqspufj {
  fill: currentColor;
  d: path("M11.242 19.5H6.5q-.213 0-.357-.143T6 19t.143-.357t.357-.143h4.742l-1.246-1.246q-.14-.14-.15-.345q-.01-.203.15-.363t.354-.16t.354.16l1.888 1.889q.131.13.184.267q.053.136.053.298t-.053.298t-.184.267l-1.888 1.889q-.14.14-.345.15q-.203.01-.363-.15t-.16-.354t.16-.354zm3.258 0q-.213 0-.357-.143T14 19t.143-.357t.357-.143h3q.214 0 .357.143T18 19t-.143.357t-.357.143zM7 4.616V16.5q0 .214-.143.357T6.5 17t-.357-.143T6 16.5V4.616q0-.691.463-1.153T7.616 3h8.769q.69 0 1.153.463T18 4.616V7.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31V16.5q0 .214-.143.357T17.5 17t-.357-.143T17 16.5V4.616q0-.231-.192-.424T16.384 4H7.616q-.231 0-.424.192T7 4.615m5.588 2.472q.22-.22.22-.548q0-.33-.22-.55t-.55-.22q-.328 0-.548.22t-.22.55t.22.549t.549.22t.549-.22");
}

</style>
