<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llhp5r44e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llhp5r44e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fast-forward-bulk-round" /></template>
