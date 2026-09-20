<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulas4swoq.css';
import '../../css/w/wx0-_tbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ulas4swoq"/><path class="wx0-_tbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-jinja-open" /></template>
