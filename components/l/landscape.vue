<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr5z6m_rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="wr5z6m_rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:landscape" /></template>
