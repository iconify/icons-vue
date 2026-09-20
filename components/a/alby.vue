<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xll1rbcfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xll1rbcfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alby" /></template>
