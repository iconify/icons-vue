<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7z7izt0q.css';
import '../../css/m/mvvtxab3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="p7z7izt0q"/><path class="mvvtxab3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-microsoft-teams" /></template>
