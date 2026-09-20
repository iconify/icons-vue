<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5-fr6b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5-fr6b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-horizontal-line" /></template>
