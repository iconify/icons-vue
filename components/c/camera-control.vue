<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykjgpvbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykjgpvbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-control" /></template>
