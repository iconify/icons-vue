<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-_ho8emr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-_ho8emr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-2-ai-line" /></template>
