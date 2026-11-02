<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl49655mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl49655mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fish-off-fill" /></template>
