<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc9_4z-8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc9_4z-8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-s-circle" /></template>
