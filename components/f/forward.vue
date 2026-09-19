<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grv2xbbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="grv2xbbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:forward" /></template>
