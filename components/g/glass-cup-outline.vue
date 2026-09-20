<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxqt6j_pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:glass-cup-outline" /></template>
<style>
.vxqt6j_pk {
  fill: currentColor;
  d: path("M7.475 21q-.621 0-1.087-.404q-.467-.404-.522-1.025L4 3h16l-1.846 16.571q-.056.621-.522 1.025T16.544 21zm-.834-3.5l.225 1.962q.038.23.211.384t.404.154h9.058q.23 0 .403-.154t.212-.384l.225-1.962zm-.104-1h10.952L18.866 4H5.116zM6.64 20h10.738z");
}

</style>
