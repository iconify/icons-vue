<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxjypom5p.css';
import '../../css/h/h_yj_ybgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxjypom5p"/><path clip-rule="evenodd" class="h_yj_ybgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:camera-filled" /></template>
