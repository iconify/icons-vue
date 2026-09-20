<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6yv-o2yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6yv-o2yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exposure-fill" /></template>
