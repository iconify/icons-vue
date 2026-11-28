<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiko28bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiko28bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-xnor-solid" /></template>
