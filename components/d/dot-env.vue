<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n__6aluxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b n__6aluxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:dot-env" /></template>
