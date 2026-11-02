<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3tuxniof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3tuxniof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ice-cream-fill" /></template>
