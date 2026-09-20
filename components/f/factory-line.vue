<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_909vbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_909vbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:factory-line" /></template>
