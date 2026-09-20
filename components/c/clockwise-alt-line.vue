<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neory07pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neory07pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clockwise-alt-line" /></template>
