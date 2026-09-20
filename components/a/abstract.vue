<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8z7-1_ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8z7-1_ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:abstract" /></template>
