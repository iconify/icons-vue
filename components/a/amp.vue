<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al6wfi6pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="al6wfi6pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:amp" /></template>
