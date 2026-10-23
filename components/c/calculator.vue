<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvfti6f1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvfti6f1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calculator" /></template>
