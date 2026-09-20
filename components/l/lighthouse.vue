<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn84y0bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn84y0bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lighthouse" /></template>
