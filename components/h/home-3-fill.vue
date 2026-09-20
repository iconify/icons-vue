<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t540i99wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t540i99wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-3-fill" /></template>
