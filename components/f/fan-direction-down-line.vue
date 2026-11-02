<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbq8t_bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbq8t_bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-direction-down-line" /></template>
