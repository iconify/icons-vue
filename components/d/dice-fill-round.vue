<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yul3m_bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yul3m_bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dice-fill-round" /></template>
