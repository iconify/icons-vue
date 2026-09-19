<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8m_pv4an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r8m_pv4an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hand-thumbs-down-fill" /></template>
