<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu0p66rmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu0p66rmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-line" /></template>
