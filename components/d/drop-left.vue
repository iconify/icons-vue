<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nowzcdbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nowzcdbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:drop-left" /></template>
