<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zczsir0pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zczsir0pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lyric" /></template>
