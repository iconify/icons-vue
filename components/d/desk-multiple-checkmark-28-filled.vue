<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="whgku--mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-checkmark-28-filled" /></template>
<style>
.whgku--mo {
  fill: currentColor;
  d: path("M13 21.25A2.75 2.75 0 0 1 10.25 24h-5.5A2.75 2.75 0 0 1 2 21.25V13h11zm10.5 2a.75.75 0 0 1-1.5 0v-8.4a7.4 7.4 0 0 0 1.5-.477zm2.502-2.5a.75.75 0 0 1-1.5 0v-6.91a7.5 7.5 0 0 0 1.5-1.245zM5.75 15.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM20.5 1a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m-7.432 5.5q-.066.49-.068 1a7.46 7.46 0 0 0 1.157 4H2V9.25A2.75 2.75 0 0 1 4.75 6.5zm11.286-1.854a.5.5 0 0 0-.707 0L19 9.293l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l5-5a.5.5 0 0 0 0-.708M13.866 4a7.4 7.4 0 0 0-.594 1.5H4.804A2.75 2.75 0 0 1 7.252 4z");
}

</style>
