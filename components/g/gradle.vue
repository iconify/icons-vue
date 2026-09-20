<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9e8afbxf.css';
import '../../css/y/ye6rbxb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9e8afbxf"/><path class="ye6rbxb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:gradle" /></template>
