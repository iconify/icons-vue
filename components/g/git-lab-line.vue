<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2jsy3m_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2jsy3m_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-lab-line" /></template>
