<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgv4qp2mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgv4qp2mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-box-check-outline" /></template>
