<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxgwppb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ambulance" /></template>
<style>
.sxgwppb8w {
  fill: currentColor;
  d: path("M11.5 4.846v-3h1v3zM7.921 6.06L5.633 3.77l.713-.713l2.288 2.288zM6.577 17.423h2.692q.31 0 .52-.21q.211-.211.211-.52t-.21-.521q-.211-.21-.52-.21H6.576zm8.154 0h2.692v-1.461h-2.692q-.31 0-.52.21t-.211.52t.21.52t.52.211M16.603 11l3.148-3.142l-.627-.627l-2.521 2.51l-1.11-1.11l-.627.633zm-2.13.816q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164q1.165 1.165 1.165 2.836t-1.165 2.835t-2.835 1.165t-2.836-1.165M4.5 22q-.213 0-.357-.143T4 21.5v-7.346L5.985 8.5q.073-.238.278-.37T6.73 8h3.192V6.462h1.564q-.274.58-.419 1.208t-.145 1.31V9H6.889l-1.61 4.385h7.438q.904.944 2.087 1.462q1.183.519 2.504.519q.704 0 1.383-.154q.68-.153 1.309-.445V21.5q0 .214-.143.357T19.5 22h-.23q-.214 0-.358-.143t-.143-.357V20H5.231v1.5q0 .214-.143.357T4.73 22z");
}

</style>
