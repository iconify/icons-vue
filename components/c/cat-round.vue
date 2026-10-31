<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm3fm8bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm3fm8bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cat-round" /></template>
