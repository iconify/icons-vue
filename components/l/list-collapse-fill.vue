<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f72h2ac5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f72h2ac5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-collapse-fill" /></template>
