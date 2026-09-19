<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a84m_v2tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="a84m_v2tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-error" /></template>
