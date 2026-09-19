<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u65btl1tl.css';
import '../../css/d/dl42-n8go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u65btl1tl"/><path class="dl42-n8go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-circle-half" /></template>
