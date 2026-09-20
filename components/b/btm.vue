<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3gnr4nrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3gnr4nrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btm" /></template>
