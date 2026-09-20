<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypb0a0bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:book-2-rounded" /></template>
<style>
.ypb0a0bsm {
  fill: currentColor;
  d: path("M7.616 21q-1.085 0-1.85-.766Q5 19.47 5 18.385V6q0-1.258.871-2.129T8 3h9.385q.67 0 1.143.472q.472.472.472 1.144V16.37q0 .162-.114.286q-.115.124-.309.19q-.523.136-.858.557t-.334.98q0 .541.325.965t.848.574q.215.073.329.21t.113.304v.057q0 .214-.143.36T18.5 21zm1.625-5.374q.144-.143.144-.357V4.5q0-.213-.144-.357T8.885 4t-.357.143q-.144.144-.144.357v10.77q0 .213.144.356q.143.143.357.143q.213 0 .356-.143M7.616 20h9.363q-.285-.33-.44-.732q-.155-.4-.155-.884q0-.457.152-.87t.443-.745H7.616q-.689 0-1.152.476T6 18.385q0 .688.464 1.151T7.616 20");
}

</style>
