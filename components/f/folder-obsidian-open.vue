<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu4o5rbfd.css';
import '../../css/h/ho_37qg1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cu4o5rbfd"/><path class="ho_37qg1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-obsidian-open" /></template>
