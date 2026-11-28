<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm4ku1vqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm4ku1vqw primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:border-inside-duotone" /></template>
