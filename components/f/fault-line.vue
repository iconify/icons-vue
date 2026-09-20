<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juorm-blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juorm-blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fault-line" /></template>
