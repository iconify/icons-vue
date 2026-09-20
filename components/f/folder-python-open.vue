<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l32lerbfx.css';
import '../../css/i/irkldebla.css';
import '../../css/l/lbwm2mbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l32lerbfx"/><path class="irkldebla"/><path class="lbwm2mbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-python-open" /></template>
