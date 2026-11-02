<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-x-d5bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-x-d5bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bring-to-front-line" /></template>
