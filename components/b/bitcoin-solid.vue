<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjq0dtskx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjq0dtskx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bitcoin-solid" /></template>
