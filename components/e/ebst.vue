<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoay7kesa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yoay7kesa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ebst" /></template>
