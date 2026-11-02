<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk9ih1bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk9ih1bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-big-left-dash-fill" /></template>
