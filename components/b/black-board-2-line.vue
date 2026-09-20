<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu624--wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu624--wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:black-board-2-line" /></template>
