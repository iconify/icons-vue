<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hre7pb13f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hre7pb13f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:circle" /></template>
