<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f08glvb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f08glvb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:back-fill" /></template>
