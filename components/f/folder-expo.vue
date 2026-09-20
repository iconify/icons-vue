<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5-wbctd.css';
import '../../css/w/w71itubsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ch5-wbctd"/><path class="w71itubsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-expo" /></template>
