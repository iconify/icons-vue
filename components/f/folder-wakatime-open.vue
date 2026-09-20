<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxf38ybrm.css';
import '../../css/q/qrlb8jbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yxf38ybrm"/><path class="qrlb8jbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-wakatime-open" /></template>
