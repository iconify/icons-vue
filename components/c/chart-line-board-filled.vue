<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wly-g5b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wly-g5b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-line-board-filled" /></template>
