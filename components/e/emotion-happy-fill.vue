<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjmoh7xin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjmoh7xin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-happy-fill" /></template>
