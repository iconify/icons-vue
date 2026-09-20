<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8v7vu7pd.css';
import '../../css/u/uxjr5m63m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c8v7vu7pd"/><path class="uxjr5m63m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-controller" /></template>
