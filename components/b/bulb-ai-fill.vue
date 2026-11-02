<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkrr3nbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkrr3nbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-ai-fill" /></template>
