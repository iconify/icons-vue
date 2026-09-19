<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p91smn2yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p91smn2yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:category" /></template>
