<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hctg_b4vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-output-outline-sharp" /></template>
<style>
.hctg_b4vx {
  fill: currentColor;
  d: path("M4 20v-5h1v3.292l3.6-3.6l.708.708l-3.6 3.6H9v1zm11 0v-1h3.292l-3.6-3.6l.708-.708l3.6 3.6V15h1v5zM8.6 9.308L5 5.708V9H4V4h5v1H5.708l3.6 3.6zm6.8 0l-.708-.708l3.6-3.6H15V4h5v5h-1V5.708zM12 13.327q-.556 0-.941-.386q-.386-.385-.386-.941t.386-.941t.941-.386t.941.386q.386.385.386.941t-.386.941t-.941.386");
}

</style>
