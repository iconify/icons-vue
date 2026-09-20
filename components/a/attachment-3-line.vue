<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhtoks96l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhtoks96l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:attachment-3-line" /></template>
