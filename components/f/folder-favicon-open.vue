<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtmc67bsf.css';
import '../../css/v/vq1grpt4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jtmc67bsf"/><path class="vq1grpt4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-favicon-open" /></template>
