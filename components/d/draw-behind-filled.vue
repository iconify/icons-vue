<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeo6ylbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeo6ylbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:draw-behind-filled" /></template>
