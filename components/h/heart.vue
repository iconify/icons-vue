<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgqwb1bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqwb1bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:heart" /></template>
