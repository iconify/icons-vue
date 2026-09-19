<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdl6qwbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdl6qwbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bed" /></template>
