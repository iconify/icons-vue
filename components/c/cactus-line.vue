<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz8rysb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz8rysb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cactus-line" /></template>
