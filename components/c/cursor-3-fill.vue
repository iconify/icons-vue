<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-0pb5juk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-0pb5juk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-3-fill" /></template>
