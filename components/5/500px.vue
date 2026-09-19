<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4zmhql4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d4zmhql4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:500px" /></template>
