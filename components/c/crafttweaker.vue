<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay1z2s6ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":512};
const content = `<path class="ay1z2s6ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:crafttweaker" /></template>
