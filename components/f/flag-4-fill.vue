<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-9jjtbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-9jjtbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-4-fill" /></template>
