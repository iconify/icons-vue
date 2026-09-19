<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8n81hbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8n81hbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dock-right" /></template>
