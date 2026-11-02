<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntkb4qi-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntkb4qi-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-square-fill" /></template>
