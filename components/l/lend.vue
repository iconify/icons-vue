<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wil69gbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wil69gbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:lend" /></template>
