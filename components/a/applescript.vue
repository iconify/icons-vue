<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8dhdabqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c8dhdabqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:applescript" /></template>
