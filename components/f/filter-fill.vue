<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waicl-j-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waicl-j-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-fill" /></template>
