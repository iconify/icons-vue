<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l32lerbfx.css';
import '../../css/g/gpf9kny_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l32lerbfx"/><path class="gpf9kny_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vscode-open" /></template>
