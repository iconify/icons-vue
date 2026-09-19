<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7vnnoa5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e7vnnoa5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:aventrix" /></template>
