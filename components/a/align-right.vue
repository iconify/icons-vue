<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9-4knhbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9-4knhbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:align-right" /></template>
