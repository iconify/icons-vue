<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u66vm_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u66vm_5px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:audio" /></template>
