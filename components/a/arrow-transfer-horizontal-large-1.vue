<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5hd9r9ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5hd9r9ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-transfer-horizontal-large-1" /></template>
