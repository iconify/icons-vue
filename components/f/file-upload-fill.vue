<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg812ccef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg812ccef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-upload-fill" /></template>
