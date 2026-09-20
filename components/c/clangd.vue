<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c48zpqb1g.css';
import '../../css/a/ae2dujtsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c48zpqb1g"/><path class="ae2dujtsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:clangd" /></template>
