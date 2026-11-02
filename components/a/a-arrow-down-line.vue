<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5pgpp91l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5pgpp91l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:a-arrow-down-line" /></template>
