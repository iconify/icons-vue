<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l49ddegon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l49ddegon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:frame-fill" /></template>
