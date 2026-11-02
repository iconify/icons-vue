<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7t-_0t7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7t-_0t7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ligature-line" /></template>
