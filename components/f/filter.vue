<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4sljnbul.css';
import '../../css/h/hwbad23cb.css';
import '../../css/c/c-3m_b4or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b4sljnbul"/><path class="hwbad23cb"/><path class="c-3m_b4or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:filter" /></template>
