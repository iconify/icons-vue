<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsfyxcbeq.css';
import '../../css/f/fjqlh3bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfyxcbeq"/><path class="fjqlh3bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:coin" /></template>
