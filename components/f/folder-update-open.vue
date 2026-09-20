<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duza7ob8o.css';
import '../../css/y/ysc-gs3pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="duza7ob8o"/><path class="ysc-gs3pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-update-open" /></template>
