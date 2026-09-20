<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7l54zb3f.css';
import '../../css/y/yb1s09s6e.css';
import '../../css/a/atc24d7cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c7l54zb3f"/><g transform="translate(-9.24 -.5)"><path class="yb1s09s6e"/><rect class="atc24d7cn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-opencode" /></template>
