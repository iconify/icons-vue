<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb_xsvb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb_xsvb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-axis-3d-fill" /></template>
