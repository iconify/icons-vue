<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycekqlkyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ycekqlkyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital3" /></template>
