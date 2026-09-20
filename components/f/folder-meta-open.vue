<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axydisbik.css';
import '../../css/n/ns67zpbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="axydisbik"/><path class="ns67zpbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-meta-open" /></template>
