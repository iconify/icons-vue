<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtmc67bsf.css';
import '../../css/z/zaro8kx4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jtmc67bsf"/><path class="zaro8kx4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-television-open" /></template>
