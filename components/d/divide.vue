<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7m_grmss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i7m_grmss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:divide" /></template>
