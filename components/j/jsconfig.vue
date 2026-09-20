<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nis8n537v.css';
import '../../css/r/rodc0loeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nis8n537v"/><path class="rodc0loeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:jsconfig" /></template>
