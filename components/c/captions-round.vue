<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7yuivz8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7yuivz8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:captions-round" /></template>
