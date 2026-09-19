<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yihsm4bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yihsm4bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:dropbox" /></template>
