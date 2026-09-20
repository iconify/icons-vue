<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hha2vm2py.css';
import '../../css/c/cdocj7brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hha2vm2py"/><path class="cdocj7brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-stencil-open" /></template>
