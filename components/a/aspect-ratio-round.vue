<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myj5jg_sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myj5jg_sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aspect-ratio-round" /></template>
