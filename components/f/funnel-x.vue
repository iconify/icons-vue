<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb-xcib8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb-xcib8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:funnel-x" /></template>
