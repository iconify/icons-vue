<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfrfckibg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfrfckibg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eraser-fill" /></template>
