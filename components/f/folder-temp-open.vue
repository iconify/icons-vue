<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls8n74bvk.css';
import '../../css/z/zj4ty50ji.css';
import '../../css/i/ihz108blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ls8n74bvk"/><path class="zj4ty50ji"/><path class="ihz108blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-temp-open" /></template>
