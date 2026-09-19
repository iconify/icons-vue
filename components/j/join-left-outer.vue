<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_cmk6bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m_cmk6bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:join-left-outer" /></template>
