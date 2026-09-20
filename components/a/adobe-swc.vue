<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfsq92b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pfsq92b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:adobe-swc" /></template>
