<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwa26nbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwa26nbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drink-line" /></template>
