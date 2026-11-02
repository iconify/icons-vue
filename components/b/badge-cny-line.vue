<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggxo8pl6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggxo8pl6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-cny-line" /></template>
