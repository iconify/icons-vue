<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh-wn-bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh-wn-bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bone-line" /></template>
