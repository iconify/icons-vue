<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vim-_3b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vim-_3b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-candlestick-sharp" /></template>
