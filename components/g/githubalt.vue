<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a53id44pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a53id44pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:githubalt" /></template>
