<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obp0hj_be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cleaning-bucket-outline-sharp" /></template>
<style>
.obp0hj_be {
  fill: currentColor;
  d: path("M7.885 22L6.154 9h11.712l-1.731 13zm1.404-1h5.422q.231 0 .404-.154t.212-.384L16.7 10H7.275l1.398 10.462q.039.23.212.384t.403.154m4.481-6.23q.731-.732.731-1.77v-1.5h-1V13q0 .617-.441 1.059q-.442.441-1.059.441t-1.059-.441T10.5 13v-1.5h-1V13q0 1.039.73 1.77t1.77.73t1.77-.73M15 6.98q-.413 0-.707-.292T14 5.98t.293-.707T15 4.98t.707.293t.293.707t-.293.707T15 6.98m-5-1q-.82 0-1.41-.59T8 3.98q0-.839.59-1.42q.59-.58 1.41-.58q.839 0 1.42.58T12 3.98q0 .819-.58 1.41q-.581.59-1.42.59M14.712 21h-6h6.577z");
}

</style>
