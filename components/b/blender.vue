<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj3d1zxsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj3d1zxsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:blender" /></template>
