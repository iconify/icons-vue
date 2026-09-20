<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2c6m_b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2c6m_b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:add-round" /></template>
