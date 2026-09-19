<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhu63-vbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhu63-vbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-sub-down-right" /></template>
