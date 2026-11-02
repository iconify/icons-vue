<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g95tqh1qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g95tqh1qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brick-wall-shield-line" /></template>
