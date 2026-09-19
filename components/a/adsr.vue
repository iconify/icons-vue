<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0sr9obyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r0sr9obyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:adsr" /></template>
