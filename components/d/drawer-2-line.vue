<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmldzsb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmldzsb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawer-2-line" /></template>
