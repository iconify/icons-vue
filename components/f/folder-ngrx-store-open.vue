<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohx99ybum.css';
import '../../css/p/pvasu6b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ohx99ybum"/><path class="pvasu6b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-ngrx-store-open" /></template>
