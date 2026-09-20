<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsmnwl62l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsmnwl62l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bridge-2-line" /></template>
