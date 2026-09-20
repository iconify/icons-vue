<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ul88bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j7ul88bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:landing" /></template>
