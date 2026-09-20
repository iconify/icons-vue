<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_rl1pb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="m_rl1pb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:cancel" /></template>
