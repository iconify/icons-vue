<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am8x09bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am8x09bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-add" /></template>
