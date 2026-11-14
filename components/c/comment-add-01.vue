<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttxe6cpvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttxe6cpvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:comment-add-01" /></template>
