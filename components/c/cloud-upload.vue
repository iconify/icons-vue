<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7vcwzxho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1408};
const content = `<path class="j7vcwzxho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cloud-upload" /></template>
