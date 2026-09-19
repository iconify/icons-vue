<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo25m_tbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo25m_tbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:constellation" /></template>
