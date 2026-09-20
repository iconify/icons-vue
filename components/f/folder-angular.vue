<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgvb62whh.css';
import '../../css/b/by_2vzhqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vgvb62whh"/><path class="by_2vzhqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-angular" /></template>
