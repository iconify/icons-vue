<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlfs0ebmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlfs0ebmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-3d-filled" /></template>
