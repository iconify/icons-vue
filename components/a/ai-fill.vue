<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eff5bhbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eff5bhbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ai-fill" /></template>
