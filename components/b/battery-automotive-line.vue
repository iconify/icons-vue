<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m310ahvgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m310ahvgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-automotive-line" /></template>
