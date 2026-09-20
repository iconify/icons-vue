<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6m_hiuih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6m_hiuih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:global-search-filled" /></template>
