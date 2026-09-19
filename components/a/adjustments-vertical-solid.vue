<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1yarxbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1yarxbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:adjustments-vertical-solid" /></template>
