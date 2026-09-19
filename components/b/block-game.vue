<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wot1xhjvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wot1xhjvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:block-game" /></template>
