<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceuecc10c.css';
import '../../css/n/nra3bcbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ceuecc10c"/><path class="nra3bcbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-export" /></template>
