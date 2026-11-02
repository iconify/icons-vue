<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig0t7irln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig0t7irln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flip-vertical-fill" /></template>
