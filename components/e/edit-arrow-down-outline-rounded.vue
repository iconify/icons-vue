<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj97w3byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-arrow-down-outline-rounded" /></template>
<style>
.dj97w3byf {
  fill: currentColor;
  d: path("M4.808 17.116q-.348 0-.578-.23T4 16.308v-1.731q0-.323.134-.628q.133-.305.35-.522l6.891-6.794q.485-.466 1.159-.46t1.133.49l.931.943q.46.479.457 1.15t-.482 1.13l-6.846 6.77q-.217.217-.522.338t-.628.122zm.192-1h1.846l4.896-4.839l-.913-.913l-.914-.895L5 14.308zm7.456-5.552l-1.827-1.808zm6.363 7.87l-2.011-2.011q-.16-.165-.16-.357t.166-.35q.165-.16.356-.163q.192-.003.351.163l1.364 1.363V5.5q0-.213.143-.357q.143-.143.357-.143q.213 0 .356.143t.144.357v11.585l1.369-1.37q.16-.16.354-.16t.353.16t.16.354t-.16.354l-2.011 2.012q-.242.242-.565.242t-.566-.242");
}

</style>
