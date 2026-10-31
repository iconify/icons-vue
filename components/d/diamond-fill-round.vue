<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpw68zb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpw68zb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-fill-round" /></template>
