<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhtc54bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhtc54bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disabled-2-line" /></template>
