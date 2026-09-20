<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3u869byd.css';
import '../../css/a/ad-jgcc6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3u869byd"/><path class="ad-jgcc6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:godot" /></template>
