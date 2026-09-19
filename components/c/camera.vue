<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo2yj5prd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qo2yj5prd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:camera" /></template>
