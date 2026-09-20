<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynq_iix5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynq_iix5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:code-fill" /></template>
