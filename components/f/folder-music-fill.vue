<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb1wm_dxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb1wm_dxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-music-fill" /></template>
