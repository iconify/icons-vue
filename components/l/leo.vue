<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx55xbbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yx55xbbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:leo" /></template>
