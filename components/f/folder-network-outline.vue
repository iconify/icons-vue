<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uelfvgb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uelfvgb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-network-outline" /></template>
