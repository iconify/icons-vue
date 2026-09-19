<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq_qswbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nq_qswbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bottom-panel-close-filled" /></template>
