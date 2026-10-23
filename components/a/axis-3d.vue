<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9vlz4hyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9vlz4hyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:axis-3d" /></template>
