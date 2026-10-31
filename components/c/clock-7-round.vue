<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0u9elbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0u9elbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-7-round" /></template>
