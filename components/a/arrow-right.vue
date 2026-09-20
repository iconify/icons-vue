<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg566bbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg566bbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-right" /></template>
