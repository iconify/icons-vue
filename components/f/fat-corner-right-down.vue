<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxooj1cdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxooj1cdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-right-down" /></template>
