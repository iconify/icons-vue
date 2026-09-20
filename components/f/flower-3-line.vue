<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gduepcbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gduepcbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-3-line" /></template>
