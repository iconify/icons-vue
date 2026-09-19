<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry_x50bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="ry_x50bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-o" /></template>
