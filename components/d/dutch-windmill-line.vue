<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op9p-6diq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op9p-6diq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dutch-windmill-line" /></template>
