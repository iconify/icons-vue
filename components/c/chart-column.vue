<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxvu6gnwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxvu6gnwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-column" /></template>
