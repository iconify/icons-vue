<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djl89ku6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djl89ku6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2x2-check-line" /></template>
