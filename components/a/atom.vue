<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fina31b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fina31b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:atom" /></template>
