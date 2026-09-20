<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hew717ugi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hew717ugi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-left-from-line" /></template>
