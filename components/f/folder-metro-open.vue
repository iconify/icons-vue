<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhjw5tknw.css';
import '../../css/y/yedg67bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hhjw5tknw"/><path class="yedg67bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-metro-open" /></template>
