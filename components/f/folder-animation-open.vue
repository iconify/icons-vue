<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-4zo-uap.css';
import '../../css/t/tc8s89bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-4zo-uap"/><path class="tc8s89bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-animation-open" /></template>
