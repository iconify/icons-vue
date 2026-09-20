<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4b_j2glt.css';
import '../../css/h/ho_37qg1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f4b_j2glt"/><path class="ho_37qg1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-obsidian" /></template>
