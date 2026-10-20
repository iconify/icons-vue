<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdbuaia-f.css';
import '../../css/h/hl_idtb9j.css';
import '../../css/l/l2_7mneno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdbuaia-f"/><path class="hl_idtb9j"/><path class="l2_7mneno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:letter-spacing-20-bold" /></template>
