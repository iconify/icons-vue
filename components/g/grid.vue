<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2s3nidsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="h2s3nidsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:grid" /></template>
