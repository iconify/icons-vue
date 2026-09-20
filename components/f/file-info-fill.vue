<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vto9lnb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vto9lnb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-info-fill" /></template>
