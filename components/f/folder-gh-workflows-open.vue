<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s27ky2-ij.css';
import '../../css/e/e4c-z3b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s27ky2-ij"/><path class="e4c-z3b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gh-workflows-open" /></template>
