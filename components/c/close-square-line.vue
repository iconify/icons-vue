<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duv425vuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duv425vuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-square-line" /></template>
