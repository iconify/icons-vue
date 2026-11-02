<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atv00kbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atv00kbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copilot-line" /></template>
