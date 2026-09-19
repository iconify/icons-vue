<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txpzpubtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":562,"height":881};
const content = `<path class="txpzpubtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:g" /></template>
