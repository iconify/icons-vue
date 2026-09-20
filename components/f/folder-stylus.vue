<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0prf1r2a.css';
import '../../css/e/eu1xw2b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w0prf1r2a"/><path class="eu1xw2b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-stylus" /></template>
