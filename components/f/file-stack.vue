<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbcgf2hgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbcgf2hgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-stack" /></template>
