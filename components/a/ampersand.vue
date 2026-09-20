<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l286_mbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l286_mbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ampersand" /></template>
