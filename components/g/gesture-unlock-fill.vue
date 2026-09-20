<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvxx9rbxb.css';
import '../../css/i/iz0l5_b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zvxx9rbxb"/><path clip-rule="evenodd" class="iz0l5_b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gesture-unlock-fill" /></template>
