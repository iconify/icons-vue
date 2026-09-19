<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxq40_bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxq40_bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-5-filled" /></template>
