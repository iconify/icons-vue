<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qst16fb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qst16fb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevron-left" /></template>
