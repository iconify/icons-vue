<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6od7mxxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6od7mxxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:book" /></template>
