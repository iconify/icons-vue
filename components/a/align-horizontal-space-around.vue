<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srtdg4zof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srtdg4zof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-space-around" /></template>
