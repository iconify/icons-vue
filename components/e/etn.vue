<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_q-_-bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m_q-_-bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:etn" /></template>
