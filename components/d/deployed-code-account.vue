<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sogo3zcyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-account" /></template>
<style>
.sogo3zcyl {
  fill: currentColor;
  d: path("M16.235 19.908q-.162-.04-.298-.127l-2.346-1.365q-.293-.162-.442-.442T13 17.371v-2.717q0-.323.149-.603t.442-.442l2.345-1.365q.137-.086.298-.127q.162-.04.324-.04t.31.043t.286.124L19.5 13.61q.292.161.454.441q.161.28.161.603v2.717q0 .323-.161.603q-.162.28-.454.442l-2.346 1.365q-.137.08-.286.124t-.31.043t-.324-.04M3 18.615V16.97q0-.69.348-1.194t.983-.802q1.217-.592 2.51-.975q1.292-.382 3.159-.382h.235q.111 0 .223.011q-.437 1.108-.38 2.546q.059 1.439.634 2.443zm4.877-8.107Q7 9.63 7 8.385t.877-2.123T10 5.385t2.123.877T13 8.385t-.877 2.123t-2.123.877t-2.123-.877m6.465 3.65l2.216 1.279l2.215-1.28l-2.215-1.272zm2.658 4.7l2.23-1.281v-2.73L17 16.19zm-3.116-1.281l2.231 1.306v-2.667l-2.23-1.325z");
}

</style>
