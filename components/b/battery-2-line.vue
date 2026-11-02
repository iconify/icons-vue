<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kok1j0gdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kok1j0gdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-2-line" /></template>
