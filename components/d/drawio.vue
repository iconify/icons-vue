<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkcbc4m_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wkcbc4m_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:drawio" /></template>
