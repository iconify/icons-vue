<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu3dw4bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu3dw4bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:church-line" /></template>
