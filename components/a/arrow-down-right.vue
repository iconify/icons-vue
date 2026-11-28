<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhl4ykefx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhl4ykefx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-down-right" /></template>
