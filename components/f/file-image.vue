<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrjesu85j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrjesu85j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image" /></template>
