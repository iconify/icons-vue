<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7mm-nbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7mm-nbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clapperboard-fill" /></template>
