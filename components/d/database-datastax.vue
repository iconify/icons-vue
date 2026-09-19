<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nygz9v8nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nygz9v8nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-datastax" /></template>
