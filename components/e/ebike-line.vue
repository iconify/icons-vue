<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vygf5iblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vygf5iblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ebike-line" /></template>
