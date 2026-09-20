<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpfg2hbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpfg2hbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-fill" /></template>
