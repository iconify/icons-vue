<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u48mzcbuj.css';
import '../../css/d/d_z7b1b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u48mzcbuj"/><path class="d_z7b1b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-husky-open" /></template>
