<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_4c-ac4q.css';
import '../../css/c/cr1evbbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_4c-ac4q"/><path class="cr1evbbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-tasks-open" /></template>
