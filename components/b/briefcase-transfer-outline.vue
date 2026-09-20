<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv_3tuw6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv_3tuw6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-transfer-outline" /></template>
