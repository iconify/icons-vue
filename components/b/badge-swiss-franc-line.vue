<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgcigzbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgcigzbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-swiss-franc-line" /></template>
