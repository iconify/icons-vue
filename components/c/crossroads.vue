<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcl-ngbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jcl-ngbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:crossroads" /></template>
