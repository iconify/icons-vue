<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj6-g_0pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj6-g_0pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-2-fill" /></template>
