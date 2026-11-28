<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svm9p0buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svm9p0buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-text-refresh" /></template>
