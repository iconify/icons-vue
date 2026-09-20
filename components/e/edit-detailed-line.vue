<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgk140vne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgk140vne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:edit-detailed-line" /></template>
