<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb9_lwbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fb9_lwbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-shrink-diagonal-1" /></template>
