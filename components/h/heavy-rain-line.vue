<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl24qvkai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl24qvkai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-rain-line" /></template>
