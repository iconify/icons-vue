<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywii24byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywii24byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bunny-outline" /></template>
