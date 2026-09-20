<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgfmpsboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgfmpsboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:danger-circle" /></template>
