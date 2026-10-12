<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4e183byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4e183byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-space-around-filled" /></template>
