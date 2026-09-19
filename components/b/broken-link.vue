<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv2f5p14q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv2f5p14q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:broken-link" /></template>
