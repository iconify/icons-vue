<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkk-mftzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkk-mftzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:eraser-auto" /></template>
