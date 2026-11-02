<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6kdn1rcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6kdn1rcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-3-fill" /></template>
