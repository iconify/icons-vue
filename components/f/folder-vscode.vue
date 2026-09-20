<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phu1k1bve.css';
import '../../css/g/gpf9kny_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="phu1k1bve"/><path class="gpf9kny_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vscode" /></template>
