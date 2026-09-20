<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwdb95dxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwdb95dxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cd-projekt" /></template>
