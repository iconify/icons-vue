<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0n7mtbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0n7mtbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grip-horizontal-solid" /></template>
