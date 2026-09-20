<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvbzddb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tvbzddb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:arxiv-square" /></template>
