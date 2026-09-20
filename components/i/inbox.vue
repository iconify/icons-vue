<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbo1m_b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pbo1m_b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:inbox" /></template>
