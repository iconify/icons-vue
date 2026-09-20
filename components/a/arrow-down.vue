<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co71khbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co71khbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-down" /></template>
