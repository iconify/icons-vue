<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_b9l1byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m_b9l1byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:amd" /></template>
