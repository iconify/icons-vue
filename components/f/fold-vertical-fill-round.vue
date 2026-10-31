<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3s_anb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3s_anb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fold-vertical-fill-round" /></template>
