<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqb9lzyli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqb9lzyli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-1-line" /></template>
