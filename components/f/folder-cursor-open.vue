<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulas4swoq.css';
import '../../css/p/pxb9n0nrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ulas4swoq"/><path class="pxb9n0nrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cursor-open" /></template>
