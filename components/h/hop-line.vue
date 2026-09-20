<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi25h3nne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi25h3nne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hop-line" /></template>
