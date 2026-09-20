<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyzo5sbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyzo5sbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chopsticks-line" /></template>
