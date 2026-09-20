<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1_gp021j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-account-rounded" /></template>
<style>
.y1_gp021j {
  fill: currentColor;
  d: path("M16.235 19.908q-.162-.04-.298-.127l-2.346-1.365q-.293-.162-.442-.442T13 17.371v-2.717q0-.323.149-.603t.442-.442l2.345-1.365q.137-.086.298-.127q.162-.04.324-.04t.31.043t.286.124L19.5 13.61q.292.161.454.441q.161.28.161.603v2.717q0 .323-.161.603q-.162.28-.454.442l-2.346 1.365q-.137.08-.286.124t-.31.043t-.324-.04M4.038 18.615q-.44 0-.739-.299T3 17.577v-.608q0-.69.348-1.194t.983-.802q1.361-.661 2.56-.987q1.198-.326 2.715-.376q.161 0 .292.068t.212.199t.115.27t-.015.301q-.073.327-.11.676t-.036.695q0 .5.076 1.007t.227.957q.056.161.027.298t-.11.267t-.198.199t-.28.069zm3.839-8.107Q7 9.63 7 8.385t.877-2.123T10 5.385t2.123.877T13 8.385t-.877 2.123t-2.123.877t-2.123-.877m6.465 3.65l2.216 1.279l2.215-1.28l-2.215-1.272zm2.658 4.7l2.23-1.281v-2.73L17 16.19zm-3.116-1.281l2.231 1.306v-2.667l-2.23-1.325z");
}

</style>
