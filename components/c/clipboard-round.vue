<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0i5y3njf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0i5y3njf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-round" /></template>
