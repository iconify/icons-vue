<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufs0pr4sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ufs0pr4sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:algo" /></template>
