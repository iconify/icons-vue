<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr4eov22z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr4eov22z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:file-word" /></template>
