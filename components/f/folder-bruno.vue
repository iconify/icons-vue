<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbnjf8b6m.css';
import '../../css/m/m6o8i28jv.css';
import '../../css/u/uyhftacbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fbnjf8b6m"/><path class="m6o8i28jv"/><path class="uyhftacbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-bruno" /></template>
