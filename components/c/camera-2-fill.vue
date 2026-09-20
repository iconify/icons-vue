<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd-x7cb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd-x7cb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-2-fill" /></template>
