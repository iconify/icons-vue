<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxb66cbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxb66cbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-rainstorm-line" /></template>
