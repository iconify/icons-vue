<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxgq3nehd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-arrow-down-rounded" /></template>
<style>
.kxgq3nehd {
  fill: currentColor;
  d: path("m18.82 18.435l-2.012-2.012q-.16-.165-.16-.357t.166-.35q.165-.16.356-.163q.192-.003.351.163l1.364 1.363V5.5q0-.213.143-.357q.143-.143.357-.143q.213 0 .356.143t.144.357v11.585l1.369-1.37q.16-.16.354-.16t.353.16t.16.354t-.16.354l-2.011 2.012q-.242.242-.565.242t-.566-.242M5 18v-2.654q0-1.184.7-2.123T7.508 12q-1.127-.285-1.817-1.233Q5 9.82 5 8.616V6H4q-.213 0-.357-.143T3.5 5.5t.143-.357T4 5h9.385q.213 0 .356.143t.144.357t-.144.357t-.356.143h-.962v2.616q0 1.223-.71 2.161q-.71.939-1.836 1.223q1.127.285 1.837 1.214q.709.928.709 2.132V18h.962q.213 0 .356.143t.144.357t-.144.357t-.356.143H4q-.213 0-.357-.143T3.5 18.5t.143-.357T4 18z");
}

</style>
