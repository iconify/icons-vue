<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iglgn19tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iglgn19tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-arrow-from-left" /></template>
