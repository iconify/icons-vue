<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvcj4j3lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvcj4j3lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-info-solid" /></template>
