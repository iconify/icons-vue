<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ermy3-b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ermy3-b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:doc-line" /></template>
