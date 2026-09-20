<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs6yp6sra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs6yp6sra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-snow-line" /></template>
