<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjhp8_bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjhp8_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:italic-bulk-round" /></template>
