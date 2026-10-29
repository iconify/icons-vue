<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l03o9u8jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l03o9u8jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fish-solid" /></template>
