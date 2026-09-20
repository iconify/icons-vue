<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbref9o6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gitlab" /></template>
<style>
.fbref9o6w {
  fill: currentColor;
  d: path("m11.577 19.485l-5.898-4.443q-1.083-.815-1.44-2.115t.128-2.57l2.158-5.612q.064-.17.212-.265t.317-.095q.173 0 .336.103t.225.313L9.071 9.25h5.866l1.448-4.449q.063-.21.226-.313t.335-.103q.17 0 .317.095q.148.095.211.265l2.134 5.611q.486 1.271.129 2.571t-1.44 2.115l-5.905 4.443q-.18.13-.407.13t-.408-.13");
}

</style>
