<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3jsy69az.css';
import '../../css/h/h5js46x2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b3jsy69az"/><path class="h5js46x2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:carbon-for-salesforce" /></template>
