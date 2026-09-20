<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkb61lbnd.css';
import '../../css/u/uwu1irugu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dkb61lbnd"/><path class="uwu1irugu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-element-open" /></template>
