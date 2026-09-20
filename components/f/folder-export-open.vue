<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb8w2y-mu.css';
import '../../css/n/nra3bcbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sb8w2y-mu"/><path class="nra3bcbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-export-open" /></template>
