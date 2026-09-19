<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhokkbbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhokkbbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:document-chart-bar" /></template>
