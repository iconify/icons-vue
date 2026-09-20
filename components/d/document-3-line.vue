<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeaoikbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeaoikbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:document-3-line" /></template>
