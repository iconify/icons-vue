<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccilu4bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccilu4bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:low-vision" /></template>
