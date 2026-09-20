<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj_40jb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":260,"height":256};
const content = `<path class="aj_40jb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:curseforge-light" /></template>
