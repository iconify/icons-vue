<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl9-skbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl9-skbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-3-fill" /></template>
