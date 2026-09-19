<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytyrf4ord.css';
import '../../css/i/iyx3sgnar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytyrf4ord"/><path class="iyx3sgnar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-shield-plus" /></template>
