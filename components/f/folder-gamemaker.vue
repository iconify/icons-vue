<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l47nr7bbh.css';
import '../../css/j/j3d0l-bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l47nr7bbh"/><path class="j3d0l-bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gamemaker" /></template>
