<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfc13kbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfc13kbqr primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grip-vertical-duotone" /></template>
