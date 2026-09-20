<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elqg70krt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elqg70krt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:happy-fill" /></template>
