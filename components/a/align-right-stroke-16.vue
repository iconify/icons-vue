<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8m_n-tpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h8m_n-tpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-right-stroke-16" /></template>
