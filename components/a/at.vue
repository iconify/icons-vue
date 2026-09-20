<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj2-m_bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj2-m_bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:at" /></template>
