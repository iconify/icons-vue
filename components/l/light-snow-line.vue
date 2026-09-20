<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odu7kactt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odu7kactt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:light-snow-line" /></template>
