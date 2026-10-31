<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb3n-4b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb3n-4b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-down-right-round" /></template>
