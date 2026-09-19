<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a95pulbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a95pulbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:link" /></template>
