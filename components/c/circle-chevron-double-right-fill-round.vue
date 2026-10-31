<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m62sktb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m62sktb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-double-right-fill-round" /></template>
