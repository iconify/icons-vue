<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv8-lrn5y.css';
import '../../css/d/dt86ds9dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xv8-lrn5y"/><path class="dt86ds9dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-molecule-open" /></template>
