<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3nhiorgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3nhiorgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arc-browser-line" /></template>
