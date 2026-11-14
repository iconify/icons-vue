<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7tfu3sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7tfu3sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:eraser-01" /></template>
