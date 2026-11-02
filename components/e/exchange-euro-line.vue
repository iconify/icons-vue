<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah28l45tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah28l45tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-euro-line" /></template>
