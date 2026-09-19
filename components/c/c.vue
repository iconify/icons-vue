<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc7skwb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":507,"height":671};
const content = `<path class="oc7skwb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:c" /></template>
