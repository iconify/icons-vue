<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imhqz1qfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imhqz1qfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-quote-single-left" /></template>
