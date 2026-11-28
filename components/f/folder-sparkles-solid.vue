<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1gdfy-3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1gdfy-3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-sparkles-solid" /></template>
