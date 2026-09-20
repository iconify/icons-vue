<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynjlvfb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynjlvfb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-justify-center" /></template>
