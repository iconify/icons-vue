<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnjpk8bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnjpk8bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:apple-logo-fill-round" /></template>
