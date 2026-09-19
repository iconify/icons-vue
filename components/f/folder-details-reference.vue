<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy1qi8xwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gy1qi8xwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-details-reference" /></template>
