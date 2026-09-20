<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq5q78n-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="sq5q78n-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-square-down-f" /></template>
