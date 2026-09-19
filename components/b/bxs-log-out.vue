<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgwn2bc2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgwn2bc2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-log-out" /></template>
