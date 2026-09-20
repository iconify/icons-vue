<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogqs7wb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogqs7wb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:home-solid" /></template>
