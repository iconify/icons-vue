<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do5q-pbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do5q-pbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gesture-unlock-line" /></template>
