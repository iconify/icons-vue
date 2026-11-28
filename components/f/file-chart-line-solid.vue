<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzssj_eru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzssj_eru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-chart-line-solid" /></template>
