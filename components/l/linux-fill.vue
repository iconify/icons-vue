<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7mbenbgv.css';
import '../../css/j/j2bhf764p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7mbenbgv"/><path class="j2bhf764p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:linux-fill" /></template>
