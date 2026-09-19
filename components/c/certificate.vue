<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahkf60ncm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahkf60ncm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:certificate" /></template>
