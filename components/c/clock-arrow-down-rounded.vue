<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-t57xbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clock-arrow-down-rounded" /></template>
<style>
.y-t57xbej {
  fill: currentColor;
  d: path("M4.207 16.438q-1.86-1.87-1.86-4.534t1.86-4.534T8.73 5.5t4.534 1.87t1.87 4.534t-1.87 4.534t-4.534 1.87t-4.524-1.87m5.043-4.705v-3.04q0-.214-.143-.358t-.357-.143t-.357.143t-.143.357v3.171q0 .162.056.302t.186.27l2.192 2.192q.16.16.355.15t.353-.15q.16-.16.16-.363q0-.204-.16-.364zm9.57 6.702l-2.012-2.012q-.16-.165-.16-.357t.166-.35q.165-.16.356-.163q.192-.003.351.163l1.364 1.363V5.5q0-.213.143-.357Q19.17 5 19.384 5q.213 0 .356.143t.144.357v11.585l1.369-1.37q.16-.16.354-.16t.353.16t.16.354t-.16.354l-2.011 2.012q-.242.242-.565.242t-.566-.242");
}

</style>
