<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afz92zvrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afz92zvrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-start-fill" /></template>
