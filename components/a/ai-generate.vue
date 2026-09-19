<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg1d_jgxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg1d_jgxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-generate" /></template>
