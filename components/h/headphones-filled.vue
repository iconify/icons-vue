<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enc1xxbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enc1xxbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:headphones-filled" /></template>
