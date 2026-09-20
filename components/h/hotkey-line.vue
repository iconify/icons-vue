<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mudz3pbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mudz3pbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hotkey-line" /></template>
