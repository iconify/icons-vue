<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv4h2bcjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv4h2bcjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-code-filled" /></template>
