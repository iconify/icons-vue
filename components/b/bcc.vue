<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4czoneoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4czoneoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bcc" /></template>
