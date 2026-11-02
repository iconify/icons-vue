<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5oigob1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5oigob1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-down-circle-fill" /></template>
