<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp8-r7b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp8-r7b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-download-outline" /></template>
