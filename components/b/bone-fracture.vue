<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj8-3m_yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj8-3m_yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bone-fracture" /></template>
