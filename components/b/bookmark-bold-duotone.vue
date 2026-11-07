<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts-sbuimt.css';
import '../../css/k/kxlp5qvgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts-sbuimt"/><path class="kxlp5qvgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-bold-duotone" /></template>
