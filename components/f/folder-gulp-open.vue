<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v702yrfnr.css';
import '../../css/n/nfgrvkl1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v702yrfnr"/><path class="nfgrvkl1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gulp-open" /></template>
