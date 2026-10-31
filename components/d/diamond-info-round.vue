<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuylt021t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuylt021t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-info-round" /></template>
