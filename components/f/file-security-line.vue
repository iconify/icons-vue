<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7w7mpvun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7w7mpvun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-security-line" /></template>
