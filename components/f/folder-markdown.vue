<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcjmcxbsc.css';
import '../../css/x/x23a3l-6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcjmcxbsc"/><path class="x23a3l-6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-markdown" /></template>
