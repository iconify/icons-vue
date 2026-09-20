<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd452hbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd452hbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ladder-line" /></template>
