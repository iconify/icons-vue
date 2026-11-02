<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abdmc1bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abdmc1bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-collapse-line" /></template>
