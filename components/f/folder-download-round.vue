<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bttcv_vis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bttcv_vis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-download-round" /></template>
