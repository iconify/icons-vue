<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgx_e8bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgx_e8bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:arrow-right" /></template>
