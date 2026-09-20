<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to92t-mut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-arrow-up-outline-rounded" /></template>
<style>
.to92t-mut {
  fill: currentColor;
  d: path("M4.808 17.116q-.348 0-.578-.23T4 16.308v-1.731q0-.323.134-.628q.133-.305.35-.522l6.891-6.794q.485-.466 1.159-.46t1.133.49l.931.943q.46.479.457 1.15t-.482 1.13l-6.846 6.77q-.217.217-.522.338t-.628.122zm.192-1h1.846l4.896-4.839l-.913-.913l-.914-.895L5 14.308zm7.456-5.552l-1.827-1.808zm6.429-3.648l-1.37 1.369q-.16.16-.353.16t-.354-.16t-.16-.354t.16-.354l2.011-2.011q.243-.243.566-.243t.565.243l2.012 2.011q.16.165.16.357t-.166.35q-.166.16-.357.163t-.351-.162L19.884 6.92V18.5q0 .214-.143.357t-.356.143t-.357-.143t-.143-.357z");
}

</style>
