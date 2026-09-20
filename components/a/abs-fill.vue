<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikvcxz5-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikvcxz5-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:abs-fill" /></template>
