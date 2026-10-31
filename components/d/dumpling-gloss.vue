<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp8n_7c6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k zp8n_7c6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dumpling-gloss" /></template>
