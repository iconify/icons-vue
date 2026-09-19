<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc6pa5cqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qc6pa5cqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:compass-solid" /></template>
