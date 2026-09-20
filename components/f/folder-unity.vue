<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_ztdbjh.css';
import '../../css/u/u9fcxra5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ru_ztdbjh"/><path class="u9fcxra5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-unity" /></template>
