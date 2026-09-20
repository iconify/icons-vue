<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5u4lfsns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5u4lfsns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bar-chart" /></template>
