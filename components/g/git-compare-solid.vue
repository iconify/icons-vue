<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv18b4bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv18b4bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-compare-solid" /></template>
