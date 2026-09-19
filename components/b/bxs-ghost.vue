<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0x9rfb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0x9rfb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-ghost" /></template>
