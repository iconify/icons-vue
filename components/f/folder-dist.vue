<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb5pi-bnv.css';
import '../../css/c/c3tt83vyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tb5pi-bnv"/><path class="c3tt83vyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-dist" /></template>
