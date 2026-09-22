<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0rq95s9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-line" /></template>
<style>
.e0rq95s9d {
  fill: currentColor;
  d: path("m9.896 20l1-1H21v1zM4 20v-2.52L17.18 4.288q.122-.121.324-.204t.41-.083q.188 0 .377.076q.19.076.355.216l1.068 1.073q.14.166.213.355q.073.19.073.372q0 .208-.08.407t-.207.326L6.52 20zM17.504 7.589L19 6.111L17.889 5l-1.477 1.496z");
}

</style>
