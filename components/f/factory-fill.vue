<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9_rs5b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9_rs5b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:factory-fill" /></template>
