<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5qc2sb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5qc2sb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:injection-line" /></template>
