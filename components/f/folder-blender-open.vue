<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpyz49q5o.css';
import '../../css/h/hyjsfrrwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gpyz49q5o"/><path class="hyjsfrrwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-blender-open" /></template>
