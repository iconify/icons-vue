<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqcxf6bxf.css';
import '../../css/b/b13va5b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vqcxf6bxf"/><path class="b13va5b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:compass-alt-o" /></template>
