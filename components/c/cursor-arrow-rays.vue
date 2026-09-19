<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu67iibzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu67iibzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cursor-arrow-rays" /></template>
